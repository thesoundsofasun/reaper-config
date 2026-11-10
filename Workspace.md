# Interface and Workspace Customization

## Layouts and Visual Positioning (Main Window & Mixer)

Use the **Options** menu or right-click the specific panels to apply these visual tweaks:

- Mixer: Master Track Show on the right side of the mixer: **On**
- Mixer: Show multiple rows of tracks when size permits: **Off**
- Options: Show FX inserts in TCP (when size permits): **On**
- Options: Show sends in TCP (when size permits): **On**
- Options: Show all takes (when room): **Off** *(Disable this option)*

## Themes & Theme Adjuster
*   **Installation steps:**
  - Download [Reapertips Theme](https://reapertips.com/products/reapertips-theme) and [AEHAZE Theme Tweaks](https://github.com/thesoundsofasun/reaper-config/blob/main/REAPER/ColorThemes/AEHAZE%20Theme%20Tweaks.zip)
  - Extract `Reapertips Theme.ReaperThemeZip` theme archive
  - Drop files from `AEHAZE Theme Tweaks.zip` into extracted folder 
  - Execute `run.sh` script inside of extracted Reapertips Theme folder
  - Select newly created `AEHAZE folder` and `AEHAZE.ReaperTheme` file and compress them into `AEHAZE.zip` archive
  - Rename `AEHAZE.zip` archive to `AEHAZE.ReaperThemeZip` and place in `REAPER/ColorThemes` directory
  - Download matching `[libSwell-user.colortheme](https://github.com/thesoundsofasun/reaper-config/blob/main/REAPER/libSwell-user.colortheme)` and drop it in REAPER folder

### Open **Options → Themes → Theme Adjuster / Color Controls**. Apply the following settings for the **AEHAZE** theme:

- Color Controls
  - Tint: **-15**
---

## Customize menus/toolbars

Open **Options → Customize menus/toolbars**. Select the target toolbar from the dropdown. 


## Main

| Change | Toolbar Entries | Action | Icon |
| --- | --- | --- | --- |
| Remove | New Project | File: New Project | `toolbar_new.png` |
| Remove | Open Project | File: New Project | `toolbar_new.png` |
| Remove | Save Project | File: Save Project | `toolbar_save.png` |
| Remove | Undo | Edit: Undo | `toolbar_undo.png |
| Remove | Redo | Edit: Redo| `toolbar_redo.png |
| Remove | Marquee selection | Mouse Modifiers: Toggle arrange view override mouse modifiers A | `toolbar_marquee_cursor_selection.png` and `toolbar_marquee_cursor_selection_off.png` |
| Remove | Razor editing | Mouse Modifiers: Toggle arrange view override mouse modifiers B | `toolbar_razor_off.png` |
| Add | Toolbar: Open/close toolbar 1 | Toolbar: Open/close toolbar 1 | `toolbar_misc_up_previous.png` |
| Add | Envelope: Toggle show all active envelopes for all tracks | Envelope: Toggle show all active envelopes for all tracks (MIDI CC relative/mousewheel) | `toolbar_envelope_show.png` |
| Add | Script: mpl_LearnEditor.lua | Script: mpl_LearnEditor.lua | `toolbar_knob_parameter_visible_show.png` |
| Add | Script: mpl_ModulationEditor.lua | Script: mpl_ModulationEditor.lua | `RTH_Shape_Sine.png` |
| Add | RKES: Toggle Virtual MIDI Keyboard | RKES: Toggle Virtual MIDI Keyboard | `toolbar_misc_keyboard.png` |





### Main toolbar

**Remove the following default buttons:**
- New Project
- Open Project
- Save Project
- Marquee selection
- Undo
- Redo
- Razor editing

**Add the following actions:**
- Toolbar: Open/close toolbar 1 → **Icon: `toolbar_misc_up_previous.png`**
- Envelope: Toggle show all active envelopes for all tracks
- Script: mpl_LearnEditor.lua 
- Script: mpl_ModulationEditor.lua → **Icon: `RTH_Shape_Sine.png`** *(From Reatips pack)*
- Script: HPRSSN Hidden VKB: Toggle → **Icon: `toolbar_misc_keyboard.png`** *(Replaces the Computer MIDI Keyboard action)*

### Floating toolbar 1

**Add the following actions:**
- Script: BirdBird_Item Modifiers.lua
- Script: acendan_reaperblog_Duplicate items or tracks depending on focus and time selection.lua → **Text Icon: `Duplicate`**
- Item: Glue items, ignoring time selection → **Text Icon: `Glue`**
- Item properties: Toggle take reverse → **Text Icon: `Reverse`**
- Script: Stretch selected media items by x0.5.lua → **Text Icon: `/2`**
- Script: Stretch selected media items by x2.lua → **Text Icon: `x2`**
- Item: Quantize item positions to grid... → **Icon: `toolbar_quant_off.png`**

### MIDI piano roll toolbar

**Add the following actions:**
- Options: Preview notes when inserting or editing → **Icon: Headphones**
- Script: Stretch selected MIDI notes positions by x0.5 MPL → **Text Icon: `/2`**
- Script: Stretch selected MIDI notes positions by x2 MPL → **Text Icon: `x2`**
- Set note ends to start of next note (legato) → **Text Icon: `Legato`**
- Edit: Duplicate events within time selection → **Text Icon: `Duplicate`**
- Humanize notes... → **Text Icon: `Humanize`**
- View: Zoom to content → **Icon: `toolbar_midi_zoom.png`**
