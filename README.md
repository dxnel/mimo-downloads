# Mimo downloads

Mimo is a cozy, local home for your music. This repository holds its macOS test builds and update files. The app's source code is kept separately in a private repository.

## Alpha builds

Mimo is being tested on **Apple Silicon Macs** before 1.0. Choose a version from [Releases](https://github.com/dxnel/mimo-downloads/releases), download its `Mimo_<version>_aarch64.dmg`, open the DMG, and drag Mimo into Applications. The release page includes a SHA-256 checksum if you want to verify your download.

These builds use free ad-hoc signing and are not notarized by Apple. If macOS blocks the first launch, try opening Mimo and then use **System Settings → Privacy & Security → Open Anyway** if macOS offers it. [Apple explains this approval step](https://support.apple.com/en-us/102445). Do not disable macOS security settings globally.

Mimo keeps your library metadata on your Mac and leaves your audio in its original folders. Export a library backup from Settings before testing an update; that backup does not include the audio files.

Update checks live in **About Mimo** inside the app. The `alpha/latest.json` file serves the alpha update channel; the DMG is for a new installation, while the signed archive attached to each release is for in-app updates.
