# Chord Desktop

Release builds of Chord Desktop. This repository holds only releases. The source is in the Chord
repository.

Linux: `.AppImage`, `.deb` or `.rpm`. Windows: the `-setup.exe` installer. macOS: the `.dmg`. The builds are not signed with a Developer ID yet. Windows SmartScreen warns once. On macOS, open System Settings → Privacy & Security and click Open Anyway. For 0.1.0-beta.1, which is not signed at all, macOS says Chord is damaged: run `xattr -dr com.apple.quarantine /Applications/Chord.app` once.

**[Download the latest release](https://github.com/abbyfluoroethane/chord-desktop/releases/latest)**. Betas are listed as
pre-releases on the [releases page](https://github.com/abbyfluoroethane/chord-desktop/releases).

## Versions

- A release is `MAJOR.MINOR.PATCH`, tagged `v0.3.0`.
- A beta is `MAJOR.MINOR.PATCH-beta.N`, tagged `v0.3.0-beta.2+<commit>`: the version it leads to, a counter, and the commit it was built from.

Each release lists the SHA-256 of its files in `SHA256SUMS`.
