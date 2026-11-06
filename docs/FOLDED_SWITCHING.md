# Folded-window application switching (experimental)

Alt+Tab/Super+Tab can select windows that are lying folded on DEsk and unfold the chosen sheet, including folded windows in the drawer. The compositor also manages fullscreen scene visibility when focus changes so switching away from a fullscreen game doesn't leave the next window hidden.

Standalone source change against DEsk 0.1.5. There is **no AiO code**. The source anchors were checked; native compile, fullscreen and multi-monitor runtime tests remain pending. This feature may overlap the shortcut changes discussed in upstream PR #8 and will require review before either merges.