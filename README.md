# Quiver app list

An app list for [Quiver Launcher](https://github.com/tgeorgiadis/quiver-launcher) with the Linux x86-64 builds of
[espgaluda2-recomp](https://github.com/cerroverb/espgaluda2-recomp) and [futari-linux](https://github.com/cerroverb/futari-linux).

In Quiver: **Settings → Advanced → My app list**, paste

    https://raw.githubusercontent.com/cerroverb/quiver-list/main/quiver.json

then add the games from **My app list** in the App Catalog. You still supply the game yourself:
- Espgaluda II: put your `.iso` next to `espgaluda2-recomp.sh` in the installed folder; the first start extracts it.
- Futari: the release archive has no game files or shaders. Copy `game_root/`, `vulkan_spirv.bin` (and `dlc/`) from a
  zip made by the [installer page](https://cerroverb.github.io/futari-linux-installer/) into the installed folder.
