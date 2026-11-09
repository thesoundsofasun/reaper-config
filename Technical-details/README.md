# Technical comparison

[File differences](File-differences.md) · [Setting differences](Setting-differences.md) · [Theme differences](Options-themes.md) · [Action registrations](Actions-scripts.md) · [Repository URLs](Extensions-ReaPack.md) · [Exact toolbar icons](Options-toolbars.md) · [Script state](Extension-script-state.md) · [Configuration copies](settings/README.md)

Preference captions were matched to English control resources in the supplied 7.83 binary. Where the once-run INI omitted a key, selected differences were checked against the initial value used by its configuration reader. Runtime hardware negotiation is distinct from a stored value.

| Page | Control | Key | Configured | Static initial value, where resolved | Bit, where relevant |
| --- | --- | --- | --- | --- | --- |
| General | Open project(s) on startup: | loadlastproj | 19 | 17 |  |
| General → Undo | When approaching full undo memory, keep newest undo states | undomask | 23 | 3 | 4 |
| General → Keyboard/Multitouch | Prevent ALT key from focusing main menu | mousewheelmode | 16 | 2 | 16 |
| Project → Backups | Auto-save to timestamped file in project directory | saveopts | 12981 | 12977 | 4 |
| Project → Track/Send Defaults | Record config: | deftrackrecinput | 5088 | 0 |  |
| Project → Track/Send Defaults | Sends send MIDI by default | defsendflag | 256 | 0 | 256 |
| Project → Item Loop Defaults | Imported items | loopnewitems | 32 | 14 | 4 |
| Project → Item Loop Defaults | MIDI items | loopnewitems | 32 | 14 | 2 |
| Project → Item Loop Defaults | Recorded items | loopnewitems | 32 | 14 | 8 |
| Project → Item Loop Defaults | Glued items | loopnewitems | 32 | 14 | 32 |
| Audio | Warn when enabled MIDI devices are not present | errnowarn | 36 | 4 | 32 |
| Audio | Show non-standard stereo channel pairs (i.e. Input 2/Input 3 etc) | allstereopairs | 0 | 1 |  |
| Audio → Device | Sample rate: | linux_audio_srate | 48000 | — |  |
| Audio → Device | Blocksize: | linux_audio_bsize | 128 | — |  |
| Audio → Device | Disable power management if supported (requires permissions to /dev/cpu_dma_latency) | linux_disable_pm | 1 | — |  |
| Audio → Playback | Stop/repeat playback at end of project | stopprojlen | 0 | 1 |  |
| Audio → Playback | Tiny fade out on playback stop | hwfadex | 0 | 3 | 1 |
| Audio → Playback | Tiny fade in on playback start | hwfadex | 0 | 3 | 2 |
| Audio → Recording | Show preview of recording items while recording, update frequency: | recupdatems | 33 | 333 |  |
| Audio → Recording | on stop | promptendrec | 0 | 1 | 1 |
| Appearance → Ruler/Grid | Dotted grid lines | griddot | 0 | 1 |  |
| Appearance → Track Meters | Meter update frequency (Hz): | vuupdfreq | 60 | 30 |  |
| Appearance → Zoom/Scroll/Offset | Vertical zoom center: | vzoommode | 3 | 0 |  |
| Appearance → Zoom/Scroll/Offset | Horizontal zoom center: | zoommode | 3 | 0 |  |
| Editing Behavior → Envelope Display | Default pitch envelope range: | pitchenvrange | 12 | 3 |  |
| Editing Behavior → Envelope Display | Prevent mouse edits of single envelope points from moving past other envelope points | env_reduce | 15 | 1031 | 1024 |
| Editing Behavior → Automation Items | Editing baseline/amplitude in properties dialog affects pooled copies | pooledenvs | 1 | 0 | 1 |
| Editing Behavior → Mouse | Ignore mousewheel on all faders | mousewheelmode | 16 | 2 | 2 |
| Editing Behavior → MIDI Editor | Default shape for CC segments: | midiccenv | 21 | 16 |  |
| Media → MIDI | MIDI octave name display offset: | midioctoffs | 0 | 1 |  |
| Plug-ins | up | fxresize | 0 | 3 | 1 |
| Plug-ins | down | fxresize | 0 | 3 | 2 |
