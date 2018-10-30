# Gentoo wine-pba
Gentoo ebuild patchset(s), for **app-emulation/wine-staging** and **app-emulation/wine-vanilla**. Wine-pba adds a persistent buffer allocator for faster dynamic geometry in Direct3D games, running under Wine.

## ```wine-staging-pba/```

Contains wine-pba patchsets, rebased for Wine Staging, seperated into directories by Wine Git commits. These rebased wine-pba patchsets are guaranteed to apply to all child Wine Git commits, on which Wine Staging has been rebased. When a subsequent wine-pba rebase snapshot is necessary, then a new patchset directory is created for this (and so on).

## ```wine-vanilla-pba/```

Contains wine-pba patchsets, rebased for Wine, seperated into directories by Wine Git commits. These rebased wine-pba patchsets are guaranteed to apply to all child Wine Git commits. When a subsequent wine-pba rebase snapshot is necessary, then a new patchset directory is created for this (and so on).

# wine-pba

Full credit, for developing this patchset, should go to the original author Andrew Comminos [@acomminos](https://github.com/acomminos).
See: [Github: acomminos / wine-pba](https://github.com/acomminos/wine-pba). Also see: [Approaching One Driver Overhead: Making Direct3D games faster in Wine using modern OpenGL](https://comminos.com/posts/2018-02-21-wined3d-profiling.html); for the guiding principles behind his work.

Thanks also to the Arch Linux packaging work done by: **Etienne Juvigny** [@Tk-Glitch](https://github.com/Tk-Glitch).
