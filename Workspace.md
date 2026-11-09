# Themes, toolbars and extensions

## Options → Themes

Choose **Aesthetichaze + Reapertips**. It uses the loose .ReaperTheme definition and the matching .ReaperThemeZip in ColorThemes. Copy both from the configured archive. The theme-adjuster settings are stored in reaper-themeconfig.ini.

The Linux widget palette uses **SF Pro Text**. Restore libSwell.colortheme and libSwell-user.colortheme alongside REAPER, then restart. The user file sets the default font size to 12 and the menu font size to 13.

## View → Screensets/Layouts

In **Windows**, load slot **4 — Default screen set** after restoring reaper-screensets.ini. The mixer was docked and visible in both snapshots.

## Customize menus/toolbars

Right-click a toolbar and choose the customization command. Each list gives the button captions from left to right, using the spelling in your saved toolbar. A vertical bar marks a separator. To recover the exact icons and commands, restore reaper-menu.ini and the custom toolbar icons.

### Main toolbar

Toolbar: Open/close toolbar 1

Project settings... → Enable metronome → Enable auto-crossfade → Enable item grouping and track media/razor edit grouping → Toggle ripple editing → Show arrange view grid → Enable snapping → Enable locking → Move envelope points with media items

Envelope: Toggle show all active envelopes for all tracks → Script: mpl_LearnEditor.lua → Script: mpl_ModulationEditor.lua

View: Toggle mixer visible → Script: NVSD_ItemView.lua → View: Toggle show MIDI editor windows

HPRSSN Hidden VKB: Toggle

### Floating toolbar 1

Script: BirdBird_Item Modifiers.lua → Item: Quantize item positions to grid... → Duplicate → Reverse → Glue

/2 → 2x → Calculate transient guides → Clear transient guides

### Floating toolbar 3

SMB: Toggle media browser

### MIDI piano roll toolbar

Options: Preview notes when inserting or editing → Save (.mid source only) → Revert (.mid source only) → Piano roll → Named notes → Event list → Musical notation → Rectangular notes (normal mode) → Triangular notes (drum mode) → Diamond notes (drum mode) → Filter → Track List → CC selection follows note selection → Show grid → Snap to grid → Step sequencing: use all MIDI inputs for step recording → View: Zoom to content

Quantize → Duplicate → Humanize → Legato → /2 → x2

Dock editor

## Extensions → ReaPack

Install the matching Linux extensions before restoring actions that use them. The configured UserPlugins folder contains ReaPack, SWS, ReaImGui, js_ReaScriptAPI, RKES, Plugin Picker and SMB. In ReaPack, the following packages have installation receipts.


| Package | Version |
| --- | --- |
| DSG_Cartridge create track from Media Item.lua | 1.1.1 |
| ReaPack.ext | 1.2.6 |
| RobU - MIDI Ex Machina.lua | 1.3.6 |
| SMB | 0.5.1 |
| js_ReaScriptAPI.ext | 1.310 |
| reaper_imgui.ext | 0.10.0.5 |

## Actions and windows supplied by extensions

- **RKES** — Alt+B toggles the virtual keyboard. The saved settings enable focus-independent Space, exclusive arm and exclusive solo.
- **MPL RS5k manager** — Shift+D starts the background script in Main. Restore the MPL Scripts folder and its registered actions.
- **Plugin Picker** — F1 opens the picker. The saved layout uses five columns, alphabetical order, instruments first and floating plug-in windows.
- **SMB** — Floating toolbar 3 opens the sample browser. Select the saved aesthetic-haze(SMB) theme. The sample root must point to the destination’s sample directory.
- **Adaptive Grid and GridBox** — Scripts/__startup.lua invokes both FTC tools when REAPER starts.
- **Cartridge** — Ctrl+Alt+C in Main runs the custom action documented in Shortcuts. The external Cartridge plug-in must be installed.

## Track templates

Restore **Airwindows Bespoke Drums.RTrackTemplate** under TrackTemplates. Its instrument is DecentSampler.vst3.
