# Shortcuts and custom actions

Open **Actions → Show action list** and choose the section shown below. For **Remove**, select the named action and delete that shortcut. For **Add**, select the named action and assign the shortcut. When an input moves, both steps appear together.

## Main

### Wheel

| Change | Shortcut | Action |
| --- | --- | --- |
| Remove | Ctrl+Shift+Mousewheel | View: Adjust selected track heights (MIDI CC relative/mousewheel) |
| Remove | Mousewheel | View: Zoom horizontally (MIDI CC relative/mousewheel) |
| Remove | Alt+Mousewheel | View: Scroll horizontally (MIDI CC relative/mousewheel) |
| Add | Alt+Mousewheel | View: Adjust selected track heights (MIDI CC relative/mousewheel) |
| Add | Shift+Mousewheel | View: Scroll horizontally reversed (MIDI CC relative/mousewheel) |
| Remove | Ctrl+Mousewheel | View: Zoom vertically (MIDI CC relative/mousewheel) |
| Add | Ctrl+Mousewheel | View: Zoom horizontally (MIDI CC relative/mousewheel) |

### Keyboard

| Change | Shortcut | Action |
| --- | --- | --- |
| Remove | Down | View: Zoom out horizontal |
| Add | Down | Track: Go to next track |
| Remove | Up | View: Zoom in horizontal |
| Add | Up | Track: Go to previous track |
| Add | Shift+A | Item: Select all items in current time selection |
| Add | H | FX: Show/hide track/take envelope for last touched FX parameter |
| Remove | Alt+B | View: Show Virtual MIDI Keyboard |
| Add | Alt+B | RKES: Toggle Virtual MIDI Keyboard |
| Add | F1(global +) | Plugin Picker: Toggle |
| Remove | Ctrl+D | Item: Duplicate items |
| Add | Ctrl+D | Script: acendan_reaperblog_Duplicate items or tracks depending on focus and time selection.lua |
| Add | Shift+D | Script: mpl_RS5k manager (background).lua |
| Add | Ctrl+Alt+C | Custom: Create a Cartidge track from Media item |

### Controller

| Change | Shortcut | Action |
| --- | --- | --- |
| Add | MIDI Chan 16 CC 117 | Transport: Record |
| Add | MIDI Chan 16 CC 116 | Transport: Stop |
| Add | MIDI Chan 16 CC 118 | Transport: Toggle repeat |
| Add | MIDI Chan 16 CC 77 | Edit: Undo |
| Add | MIDI Chan 16 CC 115 | Transport: Play/stop |
| Add | MIDI Chan 16 CC 103 | Track: Go to next track |
| Add | MIDI Chan 16 CC 102 | Track: Go to previous track |
| Add | MIDI Chan 16 CC 76 | Options: Toggle metronome |

## MIDI Editor

### Wheel

| Change | Shortcut | Action |
| --- | --- | --- |
| Remove | Mousewheel | View: Zoom horizontally (MIDI relative/mousewheel) |
| Remove | Alt+Mousewheel | View: Scroll horizontally (MIDI relative/mousewheel) |
| Add | Alt+Mousewheel | View: Zoom vertically (MIDI relative/mousewheel) |
| Remove | Ctrl+Mousewheel | View: Zoom vertically (MIDI relative/mousewheel) |
| Add | Ctrl+Mousewheel | View: Zoom horizontally (MIDI relative/mousewheel) |
| Remove | Shift+Mousewheel | Edit: Adjust value for events (mousewheel/MIDI controller only) |
| Add | Shift+Mousewheel | View: Scroll horizontally reversed (MIDI relative/mousewheel) |

### Keyboard

| Change | Shortcut | Action |
| --- | --- | --- |
| Remove | Ctrl+Up | Edit: Move notes up one semitone |
| Remove | Ctrl+Down | Edit: Move notes down one semitone |
| Remove | Up | View: Zoom in horizontally |
| Add | Up | Edit: Move notes up one semitone |
| Remove | Down | View: Zoom out horizontally |
| Add | Down | Edit: Move notes down one semitone |
| Remove | Shift+Up | Edit: Increase pitch cursor one semitone |
| Add | Shift+Up | Edit: Move notes up one octave |
| Remove | Shift+Down | Edit: Decrease pitch cursor one semitone |
| Add | Shift+Down | Edit: Move notes down one octave |

## Custom actions

In the Main section, create each named action and add the commands in the order shown.

### Computer MIDI Keyboard

1. Virtual MIDI Keyboard: Send all input to VKB
2. View: Show Virtual MIDI Keyboard

### toggle record

1. Transport: Record

### Create a Cartidge track from Media item

1. Item: Render items to new take
2. DSG_Cartridge create track from Media Item.lua

The exact keymap in Technical-details.zip also retains three unlabelled input records and the global F1 routing record.
