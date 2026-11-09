## Extensions
Drop downloaded files in REAPER/UserPlugins directory
| UserPlugins | Notes |
| --- | --- |
| [ReaPack](https://reapack.com/) (for newer distros install `libxml2_2.13.x86_64` binary) | package manager for managing third-party scripts and extensions |
| [RKES (Reaper Keyboard Enhancement Scripts)](https://github.com/thesoundsofasun/reaper-config/blob/main/REAPER/UserPlugins/reaper_RKES-x64.so) | fixes keyboard focus issues in JUCE plugins and adds helpful features |
| [Plugin Picker by DSGDnB](https://dsgdnb.com/reaper-plugin-picker/) + [Plugin Picker config](https://github.com/thesoundsofasun/reaper-config/blob/main/REAPER/PluginPicker/config.json) (drop config.json in REAPER/PluginPicker directory) | plugin manager |
| [SWS Extensions](https://sws-extension.org/) | adds advanced track management, loudness analysis, macro programming, and automation features |
| js_ReaScriptAPI.ext | 1.310 |
| reaper_imgui.ext | 0.10.0.5 |


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
