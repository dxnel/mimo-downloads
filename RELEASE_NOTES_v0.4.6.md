# Mimo 0.4.6 · Alpha

- A more consistent interface with borderless controls, quieter theme-aware focus, and subtle page, dialog, and menu animations.
- Right-click menus avoid unnecessary redraws, selected stack icons stay outlined, and repeated track counts have been removed.
- Library pages now have Play and Shuffle buttons, and playlists have a Scan BPM & key button.
- Scanning reads explicit BPM and key labels from filenames first and can correct earlier scan estimates while preserving manual edits. Audio tempo detection handles weak offbeats more carefully.
- BPM, key, and duration now appear as compact badges. Musical keys have consistent colors, and key rules offer a selection of keys plus custom values.
- Durations are read for imported stacks, missing durations are scanned at startup, and refreshing a stack rereads durations.
- Home list backgrounds are more consistent, scan progress bars follow the theme, and development sessions show a build ID in About Mimo.

## Download

Apple Silicon macOS: download `Mimo-0.4.6.dmg`, open it, and drag Mimo into Applications. Existing installations can use the in-app updater.

Build: `M00040620261024124251434498C9`

SHA-256 checksums are attached as `SHA256SUMS.txt`.
