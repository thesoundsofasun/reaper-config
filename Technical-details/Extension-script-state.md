# Extension windows and actions → Script settings and startup actions

Scripts/__startup.lua invokes the FTC adaptive grid action and GridBox. Restore the corresponding scripts and registrations first. Each section below comes from reaper-extstate.ini. Separate keyboard extension sections are distinct saved records. A section on disk alone does not establish that its script currently runs.

## Default 7.0 Theme Adjuster

| Field | Configured |
| --- | --- |
| activePage | Generic_Global |
| chosenPalette | VICE |
| dock | 0.0 |
| wndh | 757.0 |
| wndw | 1030.0 |
| wndx | 384.0 |
| wndy | 155.0 |

## Default_6.0 theme adjuster

| Field | Configured |
| --- | --- |
| activeLayoutMcp | A |
| activeLayoutTcp | A |
| dock | 0.0 |
| editPage | 1 |
| editPage2 | 1 |
| paletteCurrent | 4 |
| showHelp | true |
| wndx | 992.0 |
| wndy | 88.0 |

## FTC.AdaptiveGrid

| Field | Configured |
| --- | --- |
| hook_cmd_name | _RS6a4ecd962e6101f6f55408dd535c25addd8de2e0 |
| main_mult | 0 |
| midi_mult | 0 |
| toolbar_entries | 32060 RS7d3c_6a4ecd962e6101f6f55408dd535c25addd8de2e0 1000;0 RS6a4ecd962e6101f6f55408dd535c25addd8de2e0 1000; |

## FTC.GridBox

| Field | Configured |
| --- | --- |
| ColorThemes\Aesthetichaze + Reapertips.ReaperTheme | t:{scale:n:1.0,bm_x:n:1571,font_size:n:13,border_color:s:0f0f0f,bm_h:n:24,attach_mode:n:4,bg_color:s:191919,bm_w:n:60,font_family:s:Ableton Sans Small,attach_x:n:314,bm_y:n:7} |
| ColorThemes\Neptune VI.ReaperTheme | t:{bm_h:n:32,bm_y:n:4,attach_x:n:727,scale:n:1.0,attach_mode:n:3,bm_x:n:1613,bm_w:n:90} |
| ColorThemes\Reapertips Theme – Dark with Light Menus.ReaperTheme | t:{scale:n:1.0,bm_x:n:1615,attach_mode:n:4,bm_h:n:26,bm_w:n:65,attach_x:n:302,bm_y:n:7} |
| ColorThemes\Reapertips_v1.90_Dark-with-Light-Menus (White Peaks + Rounded Corners + Font).ReaperTheme | t:{bm_w:n:65,bm_h:n:26,scale:n:1.0,attach_x:n:667,bm_x:n:1610,bm_y:n:6,attach_mode:n:3} |
| ColorThemes\Reapertips_v1.90_Dark-with-Light-Menus (White Peaks + Rounded Corners + Gotham font).ReaperTheme | t:{font_family:s:GothamLigh,attach_x:n:307,attach_mode:n:4,bm_x:n:1620,bm_w:n:65,bm_h:n:26,scale:n:1.0,bm_y:n:6} |
| ColorThemes\Reapertips_v1.90_Dark-with-Light-Menus (White Peaks + Rounded Corners).ReaperTheme | t:{bm_h:n:26,bm_y:n:6,bm_x:n:1617,attach_mode:n:3,bm_w:n:65,attach_x:n:674,scale:n:1.0} |
| default | t:{attach_x:n:307,bm_h:n:26,bm_x:n:1620,bm_y:n:6,attach_mode:n:4,bm_w:n:65,scale:n:1.0} |
| hide_snap | 1 |
| hook_cmd_name | _RS02de4a63cf12c72510b6da7254c3f3df05dba45c |
| is_edit_mode | b:0 |
| prev_theme_path | s:ColorThemes\&Aesthetichaze + Reapertips.ReaperTheme |

## HiddenVKB

| Field | Configured |
| --- | --- |
| enabled | 0 |
| exclusiveArm | 0 |
| layout | reaper |
| steal_keys | 0 |

## LKES

| Field | Configured |
| --- | --- |
| base | 60 |
| exclusive_arm | 1 |
| exclusive_solo | 1 |
| layout | 0 |
| velocity | 27 |

## MPL_LearnEditor

| Field | Configured |
| --- | --- |
| CONF_dock | 0 |
| CONF_filtermode | 0 |
| CONF_name | default |
| viewport_dock | 0 |
| viewport_posH | 480.0 |
| viewport_posW | 600.0 |
| viewport_posX | 392.0 |
| viewport_posY | 173.0 |

## MPL_ModulationEditor

| Field | Configured |
| --- | --- |
| CONF_dock | 0 |
| CONF_filtermode | 0 |
| CONF_name | default |
| recent_add_list | (empty) |
| recent_add_listMIDI | (empty) |
| viewport_dock | 0 |
| viewport_posH | 370.0 |
| viewport_posW | 571.0 |
| viewport_posX | 405.0 |
| viewport_posY | 388.0 |

## MPL_RS5K manager

| Field | Configured |
| --- | --- |
| CONF_autocol | 0 |
| CONF_autorenamemidinotenames | 3 |
| CONF_autoreposition | 0 |
| CONF_crop_maxlen | 30 |
| CONF_cropthreshold | -60 |
| CONF_database_map1 | (empty) |
| CONF_database_map2 | (empty) |
| CONF_database_map3 | (empty) |
| CONF_database_map4 | (empty) |
| CONF_database_map5 | (empty) |
| CONF_database_map6 | (empty) |
| CONF_database_map7 | (empty) |
| CONF_database_map8 | (empty) |
| CONF_default_velocity | 120 |
| CONF_explodeMIDItochildren_note | 36 |
| CONF_ignoreDBload | 0 |
| CONF_importselitems_removesource | 0 |
| CONF_leftpanelmode | 1 |
| CONF_loopcheck | 1 |
| CONF_loopcheck_filter | bd,bass,kick |
| CONF_loopcheck_maxlen | 8 |
| CONF_loopcheck_minlen | 2 |
| CONF_midichannel | 0 |
| CONF_midiinput | 63 |
| CONF_midioutput | -1 |
| CONF_onadd_ADSR_A | 0 |
| CONF_onadd_ADSR_D | 15 |
| CONF_onadd_ADSR_flags | 0 |
| CONF_onadd_ADSR_R | 0.02 |
| CONF_onadd_ADSR_S | 0 |
| CONF_onadd_autoLUFSnorm | -14 |
| CONF_onadd_autoLUFSnorm_toggle | 0 |
| CONF_onadd_autosetrange | 0 |
| CONF_onadd_copysubfoldname | RS5kmanager_samples |
| CONF_onadd_copytoprojectpath | 0 |
| CONF_onadd_customtemplate | (empty) |
| CONF_onadd_float | 0 |
| CONF_onadd_maxvel | 127 |
| CONF_onadd_maxvoices | 1 |
| CONF_onadd_minvel | 1 |
| CONF_onadd_newchild_trackheight | 0 |
| CONF_onadd_newchild_trackheight_lock | 0 |
| CONF_onadd_newchild_trackheightflags | 0 |
| CONF_onadd_obeynoteoff | 1 |
| CONF_onadd_ordering | 0 |
| CONF_onadd_renameinst | 0 |
| CONF_onadd_renameinst_str | RS5k |
| CONF_onadd_renametrack | 1 |
| CONF_onadd_sysexmode | 0 |
| CONF_onadd_takeparentcolor | 0 |
| CONF_onadd_whitekeyspriority | 0 |
| CONF_plugin_mapping_b64 | (empty) |
| CONF_seq_autolegato | 0 |
| CONF_seq_defaultstepcnt | 16 |
| CONF_seq_env_clamp | 1 |
| CONF_seq_force_GUIDbasedsharing | 0 |
| CONF_seq_instrumentsorder | 1 |
| CONF_seq_patlen_extendchildrenlen | 0 |
| CONF_seq_random_probability | 0.5 |
| CONF_seq_steplength | 0.25 |
| CONF_seq_stuffMIDItoLP | 0 |
| CONF_seq_treat_mouserelease_as_majorchange | 0 |
| CONF_showpadpeaks | 1 |
| CONF_showplayingmeters | 1 |
| CONF_stepmode | 0 |
| CONF_stepmode_keeplen | 1 |
| CONF_stepmode_transientahead | 0.01 |
| CONF_trackorderflags | 0 |
| INI_fix | 0 |
| UI_activeTab | Settings |
| UI_addundototabclicks | 0 |
| UI_allowdoplayeronpad | 0 |
| UI_allowshortcuts | 1 |
| UI_clickonpadplaysample | 0 |
| UI_clickonpadscrolltomixer | 0 |
| UI_clickonpadselecttrack | 1 |
| UI_col_tinttrackcoloralpha | 129 |
| UI_colRGBA_maintheme_color | 863122431 |
| UI_colRGBA_padctrl | 1330597887 |
| UI_colRGBA_paddefaultbackgr | 471604351 |
| UI_colRGBA_paddefaultbackgr_inactive | 1616928831 |
| UI_colRGBA_smplrbackgr | 4294967087 |
| UI_defaulttabsflags | 13 |
| UI_drracklayout | 0 |
| UI_drracklayout_customID | 0 |
| UI_drracklayout_custommapB64 | (empty) |
| UI_incomingnoteselectpad | 0 |
| UI_padautocolors | (empty) |
| UI_padautocolorsB64 | (empty) |
| UI_padcustomnames | (empty) |
| UI_padcustomnamesB64 | (empty) |
| UI_pads_sendnoteoff | 1 |
| UI_processoninit | 0 |
| UI_showcurrentdbmap | 0 |
| UI_transparency | 0.0 |
| UIdatabase_maps_current | 1 |
| viewport_dockID | 0 |
| viewport_posH | 301.0 |
| viewport_posW | 1920.0 |
| viewport_posX | 0.0 |
| viewport_posY | 764.0 |

## NVSD_ItemView

| Field | Configured |
| --- | --- |
| custom_color_border | 3638089983 |
| custom_color_btn_hover | 347075583 |
| custom_color_btn_off | 1111638783 |
| custom_color_btn_on | 11137791 |
| custom_color_btn_text | 3722305023 |
| custom_color_centerline | 741092607 |
| custom_color_grid_bar | 909522687 |
| custom_color_grid_beat | 640034559 |
| custom_color_info_bar_bg | 505290495 |
| custom_color_info_bar_icon | 11137791 |
| custom_color_info_bar_text | 2964369663 |
| custom_color_markers | 11137791 |
| custom_color_markers_hover | 515109887 |
| custom_color_playhead | 11137791 |
| custom_color_ruler_bg | 606348543 |
| custom_color_ruler_text | 2341178367 |
| custom_color_ruler_tick | 1616929023 |
| custom_color_waveform | 4294967295 |
| custom_color_waveform_bg | 471604479 |
| custom_color_waveform_inactive | 2779096575 |
| default_auto_fit_markers | soft |
| default_auto_show_envelopes | true |
| default_env_snap_enabled | false |
| default_envelope_lock | false |
| default_show_cue_markers | true |
| default_show_ghost_markers | true |
| default_show_tooltips | true |
| grid_adaptive | medium |
| grid_enabled | true |
| grid_fixed | 1/4 |
| grid_mode | fixed |
| grid_triplet | false |
| layout_shaped_waveform | true |
| layout_show_buttons | true |
| layout_show_controls | true |
| layout_show_fx | true |
| layout_show_scrollbar | true |
| layout_show_warp | true |
| quantize_amount | 92 |
| quantize_grid | 1/16 |
| shortcut_add_transient | ctrl+shift+I |
| shortcut_audio_preview | ctrl+Space |
| shortcut_clear | shift+C |
| shortcut_crop_to_selection | C |
| shortcut_envelope_lock | L |
| shortcut_hide_envelopes | H |
| shortcut_insert_warp_marker | ctrl+I |
| shortcut_narrow_grid | ctrl+1 |
| shortcut_open_editor | ctrl+alt+E |
| shortcut_open_settings | S |
| shortcut_preview_from_start | Enter |
| shortcut_quantize_settings | ctrl+shift+U |
| shortcut_quantize_transients | ctrl+U |
| shortcut_reset_zoom | F |
| shortcut_reverse | R |
| shortcut_scroll_hpan | shift+Scroll |
| shortcut_scroll_vzoom | ctrl+shift+Scroll |
| shortcut_scroll_zoom | ctrl+Scroll |
| shortcut_set_end_marker | Mouse5 |
| shortcut_set_fade_in | shift+Mouse4 |
| shortcut_set_fade_out | shift+Mouse5 |
| shortcut_set_start_marker | Mouse4 |
| shortcut_show_in_explorer | ctrl+F |
| shortcut_show_pan_env | shift+P |
| shortcut_show_pitch_env | shift+H |
| shortcut_show_volume_env | shift+V |
| shortcut_toggle_auto_fit | A |
| shortcut_toggle_cue_markers | M |
| shortcut_toggle_ghost_markers | G |
| shortcut_toggle_mute | Num0 |
| shortcut_toggle_snap | ctrl+4 |
| shortcut_toggle_warp | (empty) |
| shortcut_triplet_grid | ctrl+3 |
| shortcut_widen_grid | ctrl+2 |
| shortcut_zoom_in | (empty) |
| shortcut_zoom_out | (empty) |
| shortcut_zoom_to_markers | Z |
| theme | custom |
| toolbar_data | B	Item properties	40009 |
| user_theme_1_border | 3638089983 |
| user_theme_1_btn_hover | 347075583 |
| user_theme_1_btn_off | 1111638783 |
| user_theme_1_btn_on | 11137791 |
| user_theme_1_btn_text | 3722305023 |
| user_theme_1_centerline | 741092607 |
| user_theme_1_grid_bar | 909522687 |
| user_theme_1_grid_beat | 640034559 |
| user_theme_1_id | user_1771858620_1024 |
| user_theme_1_info_bar_bg | 505290495 |
| user_theme_1_info_bar_icon | 11137791 |
| user_theme_1_info_bar_text | 2964369663 |
| user_theme_1_markers | 11137791 |
| user_theme_1_markers_hover | 515109887 |
| user_theme_1_name | Reatips |
| user_theme_1_playhead | 11137791 |
| user_theme_1_ruler_bg | 606348543 |
| user_theme_1_ruler_text | 2341178367 |
| user_theme_1_ruler_tick | 1616929023 |
| user_theme_1_waveform | 4294967295 |
| user_theme_1_waveform_bg | 471604479 |
| user_theme_1_waveform_inactive | 2779096575 |
| user_theme_count | 1 |

## PARANORMALFX2

| Field | Configured |
| --- | --- |
| SETTINGS | { offline_color = 1298035455, wirethickness = 1, anim_color = 1670432511, zoom_default = 1, knobvol_color = 1238140415, tooltips = true, center_reset = false, custom_font = true, esc_close = false, background = 286331391, wire_color = -1330595329, fx_color = 828282111, zoom_max = 1, container_color = 1238140415, bypass_color = -598452993, drywet_color = 981991423, animated_highlight = true, ctrl_autocontainer = false, spacing = 10, add_btn_h = 14, v_layout = true, add_btn_w = 55, auto_color = false, parallel_color = 421802751, show_c_content_tooltips = true,} |

## RKES

| Field | Configured |
| --- | --- |
| base | 84 |
| exclusive_arm | 1 |
| exclusive_solo | 1 |
| layout | 0 |
| space_enabled | 1 |
| velocity | 61 |

## ZSRackKeys

| Field | Configured |
| --- | --- |
| auto_text | 1 |
| base | 36 |
| block | 0 |
| exclusive_arm | 1 |
| exclusive_solo | 1 |
| layout | 0 |
| velocity | 107 |

## smooth_playhead

| Field | Configured |
| --- | --- |
| enabled | 0 |
| orig_drawmode | (empty) |
| render_handover | 0 |
| style | v9\|1.00\|1.000\|00A9F2\|0\|0.00\|0\|0\|2.00\|2\|0\|1.000\|25.0\|0.000\|FFFFFF\|1\|0.15\|1\|0\|2.00\|2\|0\|1.000\|0.0\|0.150\|000000\|0\|0.15\|0\|0\|2.00\|2\|0\|1.000\|0\|6.00\|5.0\|90.0\|1.000\|1.000\|1.000\|0.150\|1.000 |


[Technical index](README.md)
