# Interface and Workspace Customization

## Layouts and Visual Positioning (Main Window & Mixer)

Use the **Options** menu or right-click the specific panels to apply these visual tweaks:

- Mixer: Master Track Show on the right side of the mixer: **On**
- Mixer: Show multiple rows of tracks when size permits: **Off**
- Options: Show FX inserts in TCP (when size permits): **On**
- Options: Show sends in TCP (when size permits): **On**
- Options: Show all takes (when room): **Off** *(Disable this option)*

## Options → Themes

*   **Installation steps:**
  - Download [Reapertips Theme](https://reapertips.com/products/reapertips-theme) and [AEHAZE Theme Tweaks](https://github.com/thesoundsofasun/reaper-config/blob/main/REAPER/ColorThemes/AEHAZE%20Theme%20Tweaks.zip)
  - Extract `Reapertips Theme.ReaperThemeZip` theme archive
  - Drop files from `AEHAZE Theme Tweaks.zip` into extracted folder 
  - Execute `run.sh` script inside of extracted Reapertips Theme folder
  - Select newly created `AEHAZE folder` and `AEHAZE.ReaperTheme` file and compress them into `AEHAZE.zip` archive
  - Rename `AEHAZE.zip` archive to `AEHAZE.ReaperThemeZip` and place in `REAPER/ColorThemes` directory
  - Download matching `[libSwell-user.colortheme](https://github.com/thesoundsofasun/reaper-config/blob/main/REAPER/libSwell-user.colortheme)` and drop it in REAPER folder

## Theme Adjuster

Open **Options → Themes → Theme Adjuster / Color Controls**. Apply the following settings for the **Aesthetichaze + Reapertips** theme:

### Color Controls
- Tint: **-40**

### Track Control Panel (TCP)
- Folder Indent / Balance Type: **1** (Standard)
- FX Pin: **Visible** (Layout A)

### Mixer Control Panel (MCP)
- Folder Indent / Balance Type: **1** (Standard)
- Mixer Divider Opacity: **79%**
- Meter Values: **Visible** (Layout A)
- Meter Values when selected: **Visible** (Layout A)

---

## Window Docking and Workspaces

Open the following windows from the **View** menu (or Action list) and right-click their title tabs to position them:

- **Mixer**: Right-click tab → **Dock Mixer in Docker**
- **Undo History**: Right-click tab → **Dock in Docker**
- **Screensets/Layouts**: Once everything is positioned, open **View → Screensets/Layouts**, go to the **Windows** tab, select slot **4**, and click **Save**. Name it **Default screen set**.

---

## Customize menus/toolbars

Open **Options → Customize menus/toolbars**. Select the target toolbar from the dropdown in the top left. Click **Add...** to insert the actions in order. Right-click an action in the list to change its icon. **Separator** means click **Add separator**.

### Main toolbar

- Toolbar: Open/close toolbar 1 → **Icon: `toolbar_misc_up_previous.png`**
- **Separator**
- Project settings... → *(Text Icon)*
- Enable metronome → *(Text Icon)*
- Enable auto-crossfade → *(Text Icon)*
- Enable item grouping and track media/razor edit grouping → *(Text Icon)*
- Toggle ripple editing → *(Text Icon)*
- Show arrange view grid → *(Text Icon)*
- Enable snapping → *(Text Icon)*
- Enable locking → *(Text Icon)*
- Move envelope points with media items → *(Text Icon)*
- **Separator**
- Envelope: Toggle show all active envelopes for all tracks → **Icon: `toolbar_envelope_show.png`**
- Script: mpl_LearnEditor.lua → **Icon: `toolbar_knob_parameter_visible_show.png`**
- Script: mpl_ModulationEditor.lua → **Icon: `RTH_Shape_Sine.png`**
- **Separator**
- View: Toggle mixer visible → **Icon: `toolbar_window_tab_mixer_tcp.png`**
- Script: NVSD_ItemView.lua → **Icon: `toolbar_audio_waveform.png`**
- View: Toggle show MIDI editor windows → **Icon: `toolbar_window_tab_midi_editor.png`**
- **Separator**
- HPRSSN Hidden VKB: Toggle → **Icon: `toolbar_misc_keyboard.png`**

### Floating toolbar 1

- Script: BirdBird_Item Modifiers.lua → **Icon: `toolbar_item_selected_cut_scissors.png`**
- Item: Quantize item positions to grid... → **Icon: `toolbar_quant_off.png`**
- Duplicate → **Icon: Text Icon (Wide)**
- Reverse → **Icon: Text Icon (Wide)**
- Glue → **Icon: Text Icon (Normal)**
- **Separator**
- Script: /2 → *(Text Icon)*
- Script: 2x → *(Text Icon)*
- Calculate transient guides → *(Text Icon)*
- Clear transient guides → *(Text Icon)*

### Floating toolbar 3

- SMB: Toggle media browser → **Icon: `toolbar_window_tab_docker_show.png`**

### MIDI piano roll toolbar

- Options: Preview notes when inserting or editing → **Icon: `toolbar_misc_phones.png`**
- Save (.mid source only) → *(Text Icon)*
- Revert (.mid source only) → *(Text Icon)*
- Piano roll → *(Text Icon)*
- Named notes → *(Text Icon)*
- Event list → *(Text Icon)*
- Musical notation → *(Text Icon)*
- Rectangular notes (normal mode) → *(Text Icon)*
- Triangular notes (drum mode) → *(Text Icon)*
- Diamond notes (drum mode) → *(Text Icon)*
- Filter → *(Text Icon)*
- Track List → *(Text Icon)*
- CC selection follows note selection → *(Text Icon)*
- Show grid → *(Text Icon)*
- Snap to grid → *(Text Icon)*
- Step sequencing: use all MIDI inputs for step recording → *(Text Icon)*
- View: Zoom to content → **Icon: `toolbar_midi_zoom.png`**
- **Separator**
- Quantize → *(Text Icon)*
- Duplicate → **Icon: Text Icon (Wide)**
- Humanize → **Icon: Text Icon (Wide)**
- Legato → **Icon: Text Icon (Wide)**
- Script: /2 → **Icon: Text Icon (Normal)**
- Script: x2 → *(Text Icon)*
- **Separator**
- Dock editor → *(Text Icon)*
