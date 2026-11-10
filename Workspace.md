# Interface and Workspace Customization

## Options → Themes

*  **Installation steps:**
  - Download [Reapertips Theme](https://reapertips.com/products/reapertips-theme) and [AEHAZE Theme Tweaks](https://github.com/thesoundsofasun/reaper-config/blob/main/REAPER/ColorThemes/AEHAZE%20Theme%20Tweaks.zip)
  - Extract `Reapertips Theme.ReaperThemeZip` theme archive
  - Drop files from `AEHAZE Theme Tweaks.zip` into extracted folder 
  - Execute `run.sh` script inside of extracted Reapertips Theme folder
  - Select newly created `AEHAZE folder` and `AEHAZE.ReaperTheme` file and compress them into `AEHAZE.zip` archive
  - Rename `AEHAZE.zip` archive to `AEHAZE.ReaperThemeZip` and place in `REAPER/ColorThemes` directory

*   **Theme Adjuster / Color Controls:** TCP/MCP scaling, element visibility rules.
*   **Linux/libSwell:** `libSwell-user.colortheme` fonts and OS-level overrides.

## Options → Layouts
*(If you use specific layouts per track rather than just global theme settings)*
*   **Track Panel:** (e.g., setting a default to 'A', 'B', or 'Large')
*   **Mixer Panel:** (e.g., setting the default Mixer layout)
*   **Master Mixer:** (e.g., hiding/showing the master fader on the right side)

## Options → Customize menus/toolbars
*(You already have a great start here. Don't forget you can also document standard right-click menus here!)*
*   **Main toolbar**
*   **Floating toolbars 1-16**
*   **MIDI piano roll toolbar**
*   **Context Menus:** (e.g., customizing `TCP context`, `Media item context`, `Ruler context` to remove clutter or add custom scripts).

## Options → Preferences... → General → Advanced UI/System tweaks
*   **HiDPI / Scaling:** Custom UI scaling settings (e.g., forcing 1.0 or 1.5 scaling).
*   **OS-specific tweaks:** (Linux/Windows specific rendering settings stored in `reaper.ini`).

## Options → Preferences... → Appearance
*   **Media item labels:** (e.g., Drawing labels above items rather than inside them).
*   **Solid edges:** Tweaks for how media items are drawn.
*   **Track Control Panels:** Tinting rules (e.g., "Tint track panel backgrounds", "Tint TCP/MCP").
*   **VU Meters/Faders:** Meter update frequency, meter colors, fader behavior.
*   **Peaks/Waveforms:** Custom waveform colors, filled vs. outlined waveforms.

## View → Screensets/Layouts
*(You have this section. This is where you map your `reaper-screensets.ini`)*
*   **Windows (Tab):** Layouts of docked/floating windows.
*   **Track Views (Tab):** Saved zoom levels and track heights.

## View → Transport
*(If this is toggled on/off, but more importantly, its positioning which happens via right-click)*
*   **Visibility:** Toggle on/off.

## View → Dockers (Multiple Dockers)
*   **Main Docker positioning:** (e.g., docked at the bottom for Mixer, docked at the left for Media Explorer).
*   **Preventing auto-docking:** (Documenting holding Ctrl/Cmd to float windows freely).

## Track → Track colors / Track icon
*   **Default colors/icons:** How manual coloring is applied (or deferred to SWS).
*   **Icon directories:** Path to `<REAPER Resource Path>/Data/track_icons`.

## Extensions → Auto Color/Icon/Layout (SWS)
*(If you use the SWS extension, this is a massive part of a custom UI workflow)*
*   **Rule Setup:** (e.g., "If track name contains *Drum*, set color to *Red*, icon to *drum.png*, layout to *B*").
*   **SWS Options:** Enabling auto-color tracking.

## Actions → Show action list (Hidden UI Tweaks)
*(Some visual tweaks only exist as Actions)*
*   **Theme development: Show theme tweak/configuration window:** (This is the crucial "Theme Tweaker" where you change WALTER fonts, grid line colors, edit cursor colors, and time selection highlight colors. Stored in the `.ReaperTheme` file).

---

## Context-Specific Positioning (Right-Click Menus)
*(Since positioning isn't always in a top menu, it's best to have a section dedicated to Right-Click behaviors)*

### [Right-Click] Transport Bar
*   **Position:** Docked top, Docked bottom, Floating, or inside Main Docker.
*   **Layout:** Center transport controls (on/off).
*   **Visibility:** Show/hide play rate, time signature, playback state.

### [Right-Click] Any Toolbar
*   **Position:** Frameless floating, Docked at top/bottom of main window, Docked in MIDI editor.

### [Right-Click] Mixer Control Panel (MCP) Master
*   **Layout:** Show folders on left side.
*   **Rows:** Show multiple rows of tracks when size permits.

### [Right-Click] Window Tabs (Docker Management)
*   **Attached position:** (Right-clicking a tab at the bottom to attach the docker to the Left/Right/Top/Bottom of the main screen).
