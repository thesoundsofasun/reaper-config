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
| AEHAZE Scripts | https://github.com/thesoundsofasun/reaper-scripts/raw/master/index.xml |
| BirdBird ReaScript Testing | https://raw.githubusercontent.com/Bird-Bird/ReaScript_Testing/main/index.xml |
| Sexan_Scripts | https://github.com/GoranKovac/ReaScripts/raw/master/index.xml |
| Saike Tools | https://raw.githubusercontent.com/JoepVanlier/JSFX/master/index.xml |
| Suzuki Scripts | https://github.com/Suzuki-Re/Suzuki-Scripts/raw/master/index.xml |
| RobU Scripts | https://github.com/RobU23/ReaScripts/raw/master/index.xml |
| DSG ReaScripts | https://github.com/Sakhnovkrg/DSG_ReaScripts/raw/master/index.xml |
| FTC Tools | https://raw.githubusercontent.com/iliaspoulakis/Reaper-Tools/master/index.xml |
| ACendan Scripts | https://acendan.github.io/reascripts/index.xml |

| Repository | Package | Notes | Mapping |
| --- | --- | --- | --- |
| ACendan Scripts | Reaper Blog Smart Duplicate | Action (Utility) | **Key: `Ctrl+D`** **`Toolbar 1`** |
| AEHAZE Scripts | RKES | Extension | **Key: `Alt+B`** **`Main toolbar`** |
| AEHAZE Scripts | Stretch selected media items by x0.5 | Script | **`Toolbar 1`** |
| AEHAZE Scripts | Stretch selected media items by x2 | Script | **`Toolbar 1`** |
| BirdBird ReaScript Testing | Item Modifiers | Script | **`Toolbar 1`** |
| DSG ReaScripts | DSG_Cartridge create track from Media Item | Action (Items Editing) | **`Key: `Ctrl+Alt+C`** |
| MPL | LearnEditor | Script | **`Main toolbar`** |
| MPL | Modulation | Script | **`Main toolbar`** |
| MPL | RS5k manager | FX specific | **`Key: `Shift+D`** |
| ReaTeam Extensions | ReaImGui: ReaScript binding for Dear ImGui | API | - |
| RobU Scripts | RobU - MIDI Ex Machina.lua | 1.3.6 | **`none`** |
| --- | js_ReaScriptAPI.ext | 1.310 |

## Actions and windows supplied by extensions

- **RKES** — Alt+B toggles the virtual keyboard. The saved settings enable focus-independent Space, exclusive arm and exclusive solo.
- **MPL RS5k manager** — Shift+D starts the background script in Main. Restore the MPL Scripts folder and its registered actions.
- **Plugin Picker** — F1 opens the picker. The saved layout uses five columns, alphabetical order, instruments first and floating plug-in windows.
- **Adaptive Grid and GridBox** — Scripts/__startup.lua invokes both FTC tools when REAPER starts.
- **Cartridge** — Ctrl+Alt+C in Main runs the custom action documented in Shortcuts. The external Cartridge plug-in must be installed.
