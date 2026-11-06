# Rectangular screenshot selection (experimental)

Press Print Screen and drag across a rectangle on the desktop, then release to capture. Ctrl+Print captures the whole screen and Alt+Print captures the focused window. Right click or Esc cancels the rectangle. The compositor temporarily stops routing pointer events to applications, then uses the existing `desk-screenshot --geometry` helper after clearing its overlay.

Standalone DEsk 0.1.5 source change. No AiO code. The geometry is currently based on the desk's primary screen, so multi-monitor selection needs testing. Native build and runtime tests pending.