# Options → Themes → Aesthetichaze + Reapertips

Select **Aesthetichaze + Reapertips** under Options → Themes. Copy the loose definition and its paired graphics ZIP into ColorThemes first. The current file records **Aesthetichaze + Reapertips.ReaperThemeZip** as its image source. The first-run archive supplies Default 7.0 and 6.0 theme packages and leaves the last selected theme implicit.

| Added theme definition or package | Location |
| --- | --- |
| Aesthetichaze + Reapertips.ReaperTheme | ColorThemes/ |
| Aesthetichaze + Reapertips.ReaperThemeZip | ColorThemes/ |
| Default_6.0.ReaperTheme | ColorThemes/ |
| Default_7.0.ReaperTheme | ColorThemes/ |
| Mydaw.ReaperTheme | ColorThemes/ |
| Mydaw.ReaperTheme + Font.ReaperTheme | ColorThemes/ |
| Neptune VI.ReaperThemeZip | ColorThemes/ |
| Old Reatips Theme.ReaperTheme | ColorThemes/ |
| Old Reatips Theme.ReaperThemeZip | ColorThemes/ |
| Reapertips Theme – Dark with Light Menus.ReaperTheme | ColorThemes/ |
| Reapertips Theme – Dark with Light Menus.ReaperThemeZip | ColorThemes/ |

**Theme adjuster.** Open the theme adjuster for the chosen theme. For the active theme the stored fields are as follows. Restore reaper-themeconfig.ini for the full set of per-theme adjustments.

| Section | Parameter | Configured |
| --- | --- | --- |
| Aesthetichaze + Reapertips | __coloradjust | 1.00000000 -40 0 0 256 192 |
| Aesthetichaze + Reapertips | param19 | 25 |
| Aesthetichaze + Reapertips | param22 | 100 |

## Theme development and Linux widget colours

Use the theme development/tweaker action for loose REAPER theme colour settings. Linux menus, fonts and native controls have a separate pair of libSwell files alongside REAPER. Each row below compares the first-run base with the configured base and user override. A dash indicates no explicit entry.

| SWELL control | First-run base | Current base | Current user |
| --- | --- | --- | --- |
| _3ddkshadow | #303030 | #141416 | #141416 |
| _3dface | #B3B3B3 | #28282a | #28282a |
| _3dhilight | #A8A8A8 | #3a3a3c | #3a3a3c |
| _3dshadow | #BFBFBF | #1c1c1e | #1c1c1e |
| button_bg | — | #3a3a3c | #323235 |
| button_hilight | #BFBFBF | #48484b | #404044 |
| button_shadow | #808080 | #202022 | #242426 |
| button_text | #262626 | #ededf0 | #dadade |
| button_text_disabled | #808080 | #77777e | #78787f |
| checkbox_bg | #E6E6E6 | #202022 | #202022 |
| checkbox_fg | #262626 | #e5e5e8 | #00a9f2 |
| checkbox_inter | #BFBFBF | #8e8e93 | #8e8e93 |
| checkbox_text | #262626 | #e5e5e8 | #dadade |
| checkbox_text_disabled | #808080 | #77777e | #78787f |
| combo_arrow | #404040 | #c7c7cc | #c7c7cc |
| combo_arrow_press | — | #ffffff | #ffffff |
| combo_bg | #BFBFBF | #363638 | #323235 |
| combo_bg2 | #BFBFBF | #363638 | #323235 |
| combo_hilight | — | #48484b | #404044 |
| combo_shadow | #808080 | #202022 | #242426 |
| combo_text | — | #ededf0 | #dadade |
| combo_text_disabled | — | #77777e | #78787f |
| default_font_face | Liberation Sans | SF Pro Text | SF Pro Text |
| default_font_size | 13 | 13 | 12 |
| edit_bg | #E6E6E6 | #1c1c1e | #202022 |
| edit_bg_disabled | #B3B3B3 | #262628 | #28282a |
| edit_bg_sel | #80c0ff | #285f9e | #245879 |
| edit_cursor | #0080ff | #f2f2f7 | #f2f2f7 |
| edit_hilight | — | #414145 | #39393d |
| edit_shadow | — | #151517 | #39393d |
| edit_text | #262626 | #ededf0 | #dadade |
| edit_text_disabled | #808080 | #77777e | #78787f |
| edit_text_sel | #ffffff | #ffffff | #e8e8ea |
| focus_hilight | #E6E6E6 | #0a84ff | #00a9f2 |
| focusrect | #ffffff | #64aaff | #00a9f2 |
| group_hilight | — | #3a3a3c | #303033 |
| group_shadow | — | #202022 | #303033 |
| group_text | #262626 | #dedee3 | #b8b8bf |
| info_bk | #A3ACAC | #3a3a3c | #3a3a3c |
| info_text | #2F3333 | #f2f2f7 | #f2f2f7 |
| label_text | — | #e5e5e8 | #dadade |
| label_text_disabled | — | #77777e | #78787f |
| listview_bg | #CCCCCC | #202022 | #202022 |
| listview_bg_sel | #466168 | #285f9e | #245879 |
| listview_bg_sel_inactive | #E6E6E6 | — | #37414a |
| listview_grid | — | #303033 | #303033 |
| listview_hdr_arrow | #606060 | #c7c7cc | #c7c7cc |
| listview_hdr_bg | — | #303032 | #2c2c2f |
| listview_hdr_hilight | — | #414145 | #38383c |
| listview_hdr_shadow | — | #202022 | #202022 |
| listview_hdr_text | — | #dedee3 | #b8b8bf |
| listview_hilight | — | — | #303033 |
| listview_shadow | — | — | #29292c |
| listview_text | #404040 | #e5e5e8 | #dadade |
| listview_text_sel | #E6E6E6 | #ffffff | #e8e8ea |
| listview_text_sel_inactive | #1A1A1A | — | #d5d8dc |
| menu_bg | — | #2c2c2e | #2c2c2f |
| menu_bg_sel | — | #0868ce | #12678e |
| menu_hilight | — | #454548 | #454548 |
| menu_scroll | #404040 | #3a3a3c | #3a3a3c |
| menu_scroll_arrow | — | #b0b0b6 | #b0b0b6 |
| menu_shadow | — | #1c1c1e | #1c1c1e |
| menu_submenu_arrow | #575757 | #b0b0b6 | #b0b0b6 |
| menu_submenu_arrow_sel | — | — | #e8e8ea |
| menu_text | — | #ededf0 | #ededf0 |
| menu_text_disabled | #808080 | #77777e | #78787f |
| menu_text_sel | — | #ffffff | #e8e8ea |
| menubar_bg | — | #28282a | #28282a |
| menubar_bg_inactive | — | — | #28282a |
| menubar_bg_sel | — | #0868ce | #12678e |
| menubar_font_size | 12 | 13 | 13 |
| menubar_height | 17 | 26 | 26 |
| menubar_margin_width | 6 | 8 | 8 |
| menubar_spacing_width | 8 | 16 | 16 |
| menubar_text | — | #ededf0 | #dadade |
| menubar_text_disabled | #808080 | #77777e | #78787f |
| menubar_text_inactive | — | — | #acaeb3 |
| menubar_text_sel | — | #ffffff | #e8e8ea |
| progress | #0080ff | #0a84ff | #00a9f2 |
| scrollbar | #202020 | #78787e | #59595f |
| scrollbar_bg | #e0e0e0 | #222224 | #252527 |
| scrollbar_fg | #a0a0a0 | #78787e | #59595f |
| scrollbar_min_thumb_height | 4 | 20 | 20 |
| scrollbar_width | 14 | 12 | 12 |
| tab_hilight | #808080 | #414145 | #414145 |
| tab_shadow | #BFBFBF | #1c1c1e | #1c1c1e |
| tab_text | #262626 | #e5e5e8 | #dadade |
| trackbar_knob | #303030 | #d1d1d6 | #d1d1d6 |
| trackbar_mark | #606060 | #77777e | #77777e |
| trackbar_track | #e0e0e0 | #1c1c1e | #1c1c1e |
| treeview_arrow | #404040 | #a1a1a6 | #a1a1a6 |
| treeview_bg | #CCCCCC | #202022 | #202022 |
| treeview_bg_sel | #466168 | #285f9e | #245879 |
| treeview_bg_sel_inactive | #E6E6E6 | — | #37414a |
| treeview_hilight | — | — | #303033 |
| treeview_shadow | — | — | #29292c |
| treeview_text | #404040 | #e5e5e8 | #dadade |
| treeview_text_sel | #E6E6E6 | #ffffff | #e8e8ea |
| treeview_text_sel_inactive | #1A1A1A | — | #d5d8dc |

**All graphics and layouts.** [1](files/ColorThemes-01.md) · [2](files/ColorThemes-02.md) · [3](files/ColorThemes-03.md) · [4](files/ColorThemes-04.md) · [5](files/ColorThemes-05.md) · [6](files/ColorThemes-06.md) · [7](files/ColorThemes-07.md) · [8](files/ColorThemes-08.md) · [9](files/ColorThemes-09.md) · [10](files/ColorThemes-10.md)

**Theme adjustment records.** [1](values/030-reaper-themeconfig-ini-01.md)

[Technical index](README.md)

### Active theme against the first-run Default 7 package

Colour and font fields · [1](theme/values-01.md) · [2](theme/values-02.md)

Graphics and WALTER files · [1](theme/graphics-01.md) · [2](theme/graphics-02.md) · [3](theme/graphics-03.md) · [4](theme/graphics-04.md) · [5](theme/graphics-05.md) · [6](theme/graphics-06.md) · [7](theme/graphics-07.md) · [8](theme/graphics-08.md) · [9](theme/graphics-09.md) · [10](theme/graphics-10.md) · [11](theme/graphics-11.md) · [12](theme/graphics-12.md) · [13](theme/graphics-13.md) · [14](theme/graphics-14.md) · [15](theme/graphics-15.md)
