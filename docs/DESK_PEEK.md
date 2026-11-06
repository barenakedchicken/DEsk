# Desk Peek: bottom-edge click (experimental)

Click a window's bottom resize border when it touches the bottom of its display to pull the paper up 20 pixels, revealing the desk and drawer. A second click restores its height. Moving over a 4px threshold converts the click to a regular resize drag. Per-window geometry state is cleared on fullscreen, maximize, unfold and unmap.

This PR is standalone for DEsk 0.1.5 without AiO code. The source anchors matched; native compilation and manual input and Xwayland regression tests remain pending.