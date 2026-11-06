# Native OSD experiment (DEsk 0.1.5)

A compositor scene overlay shows volume and brightness sliders, speaker mute, microphone mute key feedback and an F11 key indicator. It is shown over fullscreen clients but below the lock screen. F11 indicates only the keypress, not confirmed fullscreen state. Input mute uses wpctl or pactl when installed.

This PR is **standalone**: no All-in-One code, GUI, or other feature patches. The source integration was checked against 0.1.5, but native build and interactive testing remain outstanding.