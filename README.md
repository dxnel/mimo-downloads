<div align="center">
  <img src="assets/mimo-app.svg" alt="Mimo" width="104" />
  <h1>Mimo</h1>
  <p>A home for your music files.</p>
  <p><strong>Public alpha · macOS & Windows</strong><br />Made by <a href="https://www.instagram.com/lyndxnmusic/">lyndxn</a></p>
  <p><a href="https://github.com/dxnel/mimo-downloads/releases/tag/v0.5.0"><strong>Download 0.5.0</strong></a> · <a href="#get-started">Get started</a> · <a href="#feedback">Feedback</a></p>
</div>

Mimo brings your local audio folders together in one desktop library. Listen, organize ideas, save moments, and find the right track again. Your music stays in its original folders. No account required.

## Download

| Platform | Download 0.5.0 | Installation |
| --- | --- | --- |
| **macOS · Apple Silicon** | [Mimo-0.5.0.dmg](https://github.com/dxnel/mimo-downloads/releases/download/v0.5.0/Mimo-0.5.0.dmg) | Open the DMG and drag Mimo into Applications. |
| **Windows · x64** | [Mimo_0.5.0_x64-setup.exe](https://github.com/dxnel/mimo-downloads/releases/download/v0.5.0/Mimo_0.5.0_x64-setup.exe) | Run the installer and follow its steps. |

[All releases and changelogs](https://github.com/dxnel/mimo-downloads/releases) · [SHA-256 checksums](https://github.com/dxnel/mimo-downloads/releases/download/v0.5.0/SHA256SUMS.txt)

Mimo is a **public alpha**. Features and compatibility are still being refined. The Mac build is ad-hoc signed and not notarized; macOS may ask for approval in **System Settings → Privacy & Security** after you first try opening it. [Apple's guide](https://support.apple.com/en-us/102445) explains the process. The Windows installer is unsigned and may show a Windows security warning.

Intel Mac, Windows ARM, and Linux builds are not included in this release.

## Your music, easier to work with

| | What you can do |
| --- | --- |
| **A library from your folders** | Link audio folders as stacks, browse their tracks together, and keep your files where they are. |
| **Playlists that fit your workflow** | Arrange tracks yourself, or use smart playlists that update from tags, ratings, BPM, duration, and more. |
| **Markers & section loops** | Name a moment, jump back to it, and repeat a passage without typing timestamps. |
| **Details worth keeping** | Add favorites, ratings, tags, and notes. Estimate BPM and key locally when you choose to scan. |
| **Share when you're ready** | Export a playlist as an M3U8 file or a ZIP containing its audio. |

## Get started

1. **Add a stack.** Choose a folder containing audio. Mimo includes its subfolders and leaves the files in place.
2. **Start listening.** Double-click a track to play it. Use the queue to choose what comes next.
3. **Make a playlist.** Add tracks manually or choose rules for a smart playlist.
4. **Keep a moment.** Open **Track tools**, the waveform button beside the player, to add markers or select a loop.

In Track tools, drag across the waveform to select a section, try a **5s**, **10s**, or **30s** quick loop, or loop between markers. Press **M** outside text fields to add a marker; right-click a marker to edit it. Markers and loop boundaries are saved with the track.

## Updating & backups

- **Before updating:** export a library backup from **Settings → Library**. It contains Mimo's organization and metadata; back up your audio folders separately.
- **Mac:** supported installations can check in **About Mimo**. You can also install the latest DMG from the release page.
- **Windows:** download the latest installer from the release page. In-app Windows updates are not included in this release.
- **Switching back:** older Mimo versions may not understand newer icons or playlist rules. Keep a backup before trying an older version.

<details>
<summary><strong>A few alpha details</strong></summary>

- Date added is recorded for new imports. Older tracks keep an unknown date. Use **is empty** in smart-playlist date rules to include unknown dates or never-played tracks.
- Some WAV headers are rejected by the metadata or duration reader. Waveform reading also has a processing time limit; seeking, quick loops, and time editing remain available if a waveform cannot be read.
- BPM/key scans are estimates. Your own edits take precedence.
- Section looping is for listening and review; sample-accurate or gapless playback is not guaranteed.

</details>

## Feedback

Found a bug or have an idea? Contact **lyndxn** on [Instagram](https://www.instagram.com/lyndxnmusic/) or [X](https://x.com/lyndxnmusic). For a bug report, include your Mimo version, operating system, what happened, and what you expected. The build ID in **About Mimo** helps identify the exact build.

This repository contains Mimo's public downloads and update files. The app's source is maintained separately. Created by **lyndxn**.
