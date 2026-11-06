# Steam launcher identity for windows (experimental)

A standalone compositor improvement that identifies Steam runtime windows via the window process's environment and the installed Steam .desktop launcher. It does not infer identity from the last launched Steam app. Supports matching SteamAppId and related variables, including Wine/Proton Xwayland process IDs where available.

Ported against official DEsk 0.1.5 source; native build and runtime regression testing still required.
