# REAPER config for Linux

[Preferences](#preferences) · [Main window and MIDI editor](#main-window-and-midi-editor) · [Shortcuts and custom actions](Shortcuts.md) · [Themes, toolbars and extensions](Workspace.md)

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

## Preferences

Open **Options → Preferences**. Follow the headings in the left-hand tree. Each line gives the wording on screen and the value to set. **On** means check the box. **Off** means clear it.

### General

- Open project(s) on startup: **New project**

### General → Undo

- When approaching full undo memory, keep newest undo states **On**

### General → Keyboard/Multitouch

- Prevent ALT key from focusing main menu **On**

### Project → Backups

- Auto-save to timestamped file in project directory **On**

### Project → Track/Send Defaults

- Record config: **Input: MIDI → MIDI Input 32 → All Channels**
  The name comes from input slot 31 in the saved Linux device list. On another machine, check which port occupies that slot.
- Sends send MIDI by default **Off**

### Project → Item Loop Defaults


**Loop source for:**

- Imported items **Off**
- MIDI items **Off**
- Recorded items **Off**
- Glued items **Off**

### Audio

- Warn when enabled MIDI devices are not present **Off**
- Show non-standard stereo channel pairs (i.e. Input 2/Input 3 etc) **Off**

### Audio → Device

- Sample rate: **48000 Hz**
- Blocksize: **128 samples**
- Disable power management if supported (requires permissions to /dev/cpu_dma_latency) **On**

The available controls depend on **Audio system:**. The snapshots establish these stored values. They do not identify the selected backend.

### Audio → Playback

- Stop/repeat playback at end of project **Off**
- Tiny fade out on playback stop **Off**
- Tiny fade in on playback start **Off**

### Audio → Recording

- Show preview of recording items while recording, update frequency: **30 Hz**

**Prompt to save/delete/rename new files:**
- on stop **Off**
--------------------------------------------------------
- Recorded filenames: **`$track - $recpass00`**
- In-project MIDI items: **`$track-MIDI - $recpass00`**

### Appearance → Ruler/Grid

- Dotted grid lines **Off**

### Appearance → Track Meters

- Meter update frequency (Hz): **60**

### Appearance → Zoom/Scroll/Offset

- Vertical zoom center: **Track under mouse**
- Horizontal zoom center: **Mouse cursor**

### Editing Behavior → Envelope Display

- Default pitch envelope range: **12 semitones**
- Prevent mouse edits of single envelope points from moving past other envelope points **Off**

### Editing Behavior → Automation Items

- Editing baseline/amplitude in properties dialog affects pooled copies **On**

### Editing Behavior → Mouse

- Ignore mousewheel on all faders **Off**

### Editing Behavior → Mouse Modifiers

- Arrange view → middle drag → Default → **Hand scroll**
- Arrange view → middle drag → Shift → **Jog audio**
- Media item edge → double click → Default → **Item properties: Loop item source**
- MIDI piano roll → left click → Default → **Insert note**

### Editing Behavior → MIDI Editor

- Default shape for CC segments: **Bezier**

### Plug-ins

**Automatically resize FX windows:**

- up **Off**
- down **Off**

## Main window and MIDI editor

### Options

- Automatically scroll view during playback **Off**
- Trim content behind media items when editing **On**

### Transport

Right-click the transport. Set **Center transport controls** to **On**.

### MIDI editor → Options

Open a MIDI item. Set **Automatically correct overlapping notes** to **On**.

## Other saved settings

The following values are recorded in the configured profile. Their presence alone does not establish a manual change. Check them only when reproducing the same device or filename behaviour.

- **Audio → Buffering → Audio reading/processing threads:** 6. The thread count can depend on the CPU and auto-detection.

For records without a verified on-screen instruction, open [Technical-details.zip](Technical-details.zip). It contains the full comparison, optional configuration files and the evidence behind the preference checklist. Both source archives were compared directly.
