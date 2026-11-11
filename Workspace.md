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

*    **Options → Themes → Theme Adjuster / Color Controls**. 
     - Color Controls
        - Tint: **-15**
---

## Customize menus/toolbars

Open **Options → Customize menus/toolbars**. Select the target toolbar from the dropdown. 


## Main

- **Remove** following entries:

| Change | Toolbar Entries | Action | Icon |
| --- | --- | --- | --- |
| Remove | New Project | File: New Project | `toolbar_new.png` |
| Remove | Open Project | File: New Project | `toolbar_new.png` |
| Remove | Save Project | File: Save Project | `toolbar_save.png` |
| Remove | Undo | Edit: Undo | `toolbar_undo.png` |
| Remove | Redo | Edit: Redo| `toolbar_redo.png` |
| Remove | Marquee selection | Mouse Modifiers: Toggle arrange view override mouse modifiers A | `toolbar_marquee_cursor_selection.png` and `toolbar_marquee_cursor_selection_off.png` |
| Remove | Razor editing | Mouse Modifiers: Toggle arrange view override mouse modifiers B | `toolbar_razor_off.png` |

- **Add** and **Leave** following entries:

| Order Position | Change | Toolbar Entries | Action | Icon |
| --- | --- | --- | --- | --- |
| **1** | Add | Toolbar: Open/close toolbar 1 | Toolbar: Open/close toolbar 1 | `RTH_Tab_Top.png` |
| **2** | Add | -------- | -------- |  |
| **3** | Leave | Project settings... | File: Project settings... | `toolbar_projprop.png` |
| **4** | Leave | Enable metronome | Options: Toggle metronome | `toolbar_metronone.png` and `toolbar_metronone_off.png` |
| **5** | Leave | Enable auto-crossfade | Options: Auto-crossfade media items when editing | `toolbar_xfade.png` and `toolbar_xfade_off.png`|
| **6** | Leave | Enable item grouping and track media/razor edit grouping | Options: Toggle item grouping and tack media/razor edit grouping | `toolbar_group.png` |
| **7** | Leave | Toggle ripple editing | Options: Toggle ripple editing on/off | `toolbar_ripple.png` and `toolbar_ripple_off.png` |
| **8** | Leave | Show arrange view grid | Options: Toggle grid lines | `toolbar_grid.png` and `toolbar_grid_off.png` |
| **9** | Leave | Enable snapping | Options: Toggle snapping | `toolbar_snap.png` and `toolbar_snap_off.png` |
| **10** | Leave | Enable locking | Options: Toggle locking | `toolbar_lock.png` and `toolbar_lock_off.png` |
| **11** | Leave | Move envelope points with media items | Options: Move envelope points with media items | `toolbar_envitem.png` and `toolbar_envitem_off.png` |
| **12** | Add | -------- | -------- |  |
| **13** | Add | Envelope: Toggle show all active envelopes for all tracks | Envelope: Toggle show all active envelopes for all tracks (MIDI CC relative/mousewheel) | `toolbar_envelope_show.png` |
| **14** | Add | Script: mpl_LearnEditor.lua | Script: mpl_LearnEditor.lua | `toolbar_knob_parameter_visible_show.png` |
| **15** | Add | Script: mpl_ModulationEditor.lua | Script: mpl_ModulationEditor.lua | `RTH_Shape_Sine.png` |
| **16** | Add | -------- | -------- |  |
| **17** | Add | RKES: Toggle Virtual MIDI Keyboard | RKES: Toggle Virtual MIDI Keyboard | `toolbar_misc_keyboard.png` |

## Floating toolbar 1 (Toolbar 1)
| Order Position | Change | Toolbar Entries | Action | Icon |
| --- | --- | --- | --- | --- |
| **1** | Add | Script: BirdBird_Item Modifiers.lua | Script: BirdBird_Item Modifiers.lua | `toolbar_item_selected_cut_scissors.png` |
| **2** | Add | Item: Quantize item positions to grid... | Item: Quantize item positions to grid... | `toolbar_quant.png` and `toolbar_quant_off.png` |
| **3** | Add | Duplicate | Script: acendan_reaperblog_Duplicate items or tracks depending on focus and time selection.lua |  **Text double-wide icon: `Duplicate`** |
| **4** | Add | Reverse | Item properties: Toggle take reverse |  **Text double-wide icon: `Reverse`** |
| **5** | Add | Glue | Item: Glue items, ignoring time selection |  **Text double-wide icon: `Glue`** |
| **6** | Add | -------- | -------- |  |
| **7** | Add | /2 | Stretch selected media items by x0.5.lua | **Text icon: `/2`** |
| **8** | Add | 2x | Script: Stretch selected media items by x2.lua | **Text icon: `x2`**|
| **9** | Add | Calculate transient guides | Options: Toggle snapping | |
| **10** | Add | Clear transient guides | Options: Toggle locking | |

### MIDI piano roll toolbar

**Add the following actions:**
- Options: Preview notes when inserting or editing → **Icon: Headphones**
- Script: Stretch selected MIDI notes positions by x0.5 MPL → **Text Icon: `/2`**
- Script: Stretch selected MIDI notes positions by x2 MPL → **Text Icon: `x2`**
- Set note ends to start of next note (legato) → **Text Icon: `Legato`**
- Edit: Duplicate events within time selection → **Text Icon: `Duplicate`**
- Humanize notes... → **Text Icon: `Humanize`**
- View: Zoom to content → **Icon: `toolbar_midi_zoom.png`**
