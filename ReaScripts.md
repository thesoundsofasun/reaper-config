## Extensions
Drop downloaded files in REAPER/UserPlugins directory
| UserPlugins | Notes |
| --- | --- |
| [ReaPack](https://reapack.com/) (for newer distros install `libxml2_2.13.x86_64` binary) | package manager for managing third-party scripts and extensions |
| [RKES (Reaper Keyboard Enhancement Scripts)](https://github.com/thesoundsofasun/reaper-config/blob/main/REAPER/UserPlugins/reaper_RKES-x64.so) | fixes keyboard focus issues in JUCE plugins and adds helpful features |
| [Plugin Picker by DSGDnB](https://dsgdnb.com/reaper-plugin-picker/) + [Plugin Picker config](https://github.com/thesoundsofasun/reaper-config/blob/main/REAPER/PluginPicker/config.json) (drop config.json in REAPER/PluginPicker directory) | plugin manager |
| [SWS Extensions](https://sws-extension.org/) | adds advanced track management, loudness analysis, macro programming, and automation features |

## Extensions → ReaPack
Add following repositories before installing any Scripts
## Repository URLs

| Repository | URL |
| --- | --- |
| BirdBird ReaScript Testing | https://raw.githubusercontent.com/Bird-Bird/ReaScript_Testing/main/index.xml |
| Sexan_Scripts | https://github.com/GoranKovac/ReaScripts/raw/master/index.xml |
| Saike Tools | https://raw.githubusercontent.com/JoepVanlier/JSFX/master/index.xml |
| Suzuki Scripts | https://github.com/Suzuki-Re/Suzuki-Scripts/raw/master/index.xml |
| RobU Scripts | https://github.com/RobU23/ReaScripts/raw/master/index.xml |
| DSG ReaScripts | https://github.com/Sakhnovkrg/DSG_ReaScripts/raw/master/index.xml |
| FTC Tools | https://raw.githubusercontent.com/iliaspoulakis/Reaper-Tools/master/index.xml |
| ACendan Scripts | https://acendan.github.io/reascripts/index.xml |

| Repository | Package | Notes |
| --- | --- | --- |
| DSG ReaScripts | DSG_Cartridge create track from Media Item.lua | --- |
| RobU Scripts | RobU - MIDI Ex Machina.lua | 1.3.6 |
| --- | js_ReaScriptAPI.ext | 1.310 |
| --- | reaper_imgui.ext | 0.10.0.5 |

## Actions and windows supplied by extensions

- **RKES** — Alt+B toggles the virtual keyboard. The saved settings enable focus-independent Space, exclusive arm and exclusive solo.
- **MPL RS5k manager** — Shift+D starts the background script in Main. Restore the MPL Scripts folder and its registered actions.
- **Plugin Picker** — F1 opens the picker. The saved layout uses five columns, alphabetical order, instruments first and floating plug-in windows.
- **SMB** — Floating toolbar 3 opens the sample browser. Select the saved aesthetic-haze(SMB) theme. The sample root must point to the destination’s sample directory.
- **Adaptive Grid and GridBox** — Scripts/__startup.lua invokes both FTC tools when REAPER starts.
- **Cartridge** — Ctrl+Alt+C in Main runs the custom action documented in Shortcuts. The external Cartridge plug-in must be installed.
