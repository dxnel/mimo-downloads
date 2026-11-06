# Changelog

Mimo 0.5.0 is an alpha update focused on returning to the moments that matter in your music.

## New

- **Markers and section loops:** open **Track tools**, the waveform button beside the player, to save named moments and repeat a passage. Drag to select a section, adjust its handles, use 5-, 10-, or 30-second quick loops, or loop between markers. Right-click a marker to edit or delete it. Markers and loop boundaries are saved with each track; looping turns off when you change tracks or seek outside the section.
- **More smart-playlist rules:** filter by duration, date added, or last played, using calendar dates or rolling day windows. New imports record their date added; older tracks keep an unknown date. Use **is empty** for unknown dates, including never-played tracks.
- **First-launch setup:** a skippable introduction to stacks, playlists, and smart playlists, with theme and update preferences before linking your first folder.

## Changed

- Reworked the interface around shared dark surfaces, neutral hover and selection states, and clearer use of accent colors. Themes are now **Dark** and **Midnight**. Older Ocean selections become Midnight; other retired themes become Dark. Existing collection colors move to their refreshed palette equivalents.
- Made Home more compact, with library counts, Jump back in, consistent collection cards, and durations in listening history.
- Organized Settings into Appearance, Workspace, Library, Updates, and Shortcuts.
- Simplified playlist browsing to a compact list with available artist, release date, track count, duration, and description. Stacks retain grid and list layouts. Smart-playlist criteria stay in the editor rather than the overview.
- Expanded the collection icon choices and improved artwork controls, editor footers, duplicate-name checks, and description limits.
- Replaced the launch update prompt with a Home update card and release notes on demand. The after-update screen uses the same changelog.

## Fixes

- Fixed upgrade-screen detection for older installations that have no saved version history.
- Preserved older smart-playlist type and release-date metadata while hiding those fields from smart-playlist editing.
- Added streaming desktop waveform reading so files above the previous 20 MB browser limit can display their waveform.
- Improved marker labels, loop progress and playing/paused feedback, and the consistency of controls and keyboard focus.

## Download

**macOS (Apple Silicon):** download `Mimo-0.5.0.dmg`, open it, and drag Mimo into Applications.

**Windows (x64):** download `Mimo_0.5.0_x64-setup.exe` and run the installer. Windows updates are provided through the release downloads; in-app Windows updating is not enabled. The installer is unsigned and may show a Windows security warning.

Mimo is an alpha app by **lyndxn**. This Mac build uses ad-hoc signing and is not notarized by Apple; macOS may ask you to approve it in Privacy & Security. Your library stays local and audio plays from your linked folders.

## Before updating

Export a library backup from Settings → Library. Older Mimo versions may not understand newer collection icons or smart-playlist rules, so switching back to an older app with a library edited in 0.5.0 is not fully supported.

Some WAV files with nonstandard headers are rejected by the metadata and duration readers. Waveform reading has a processing time limit. If a file cannot be decoded, seeking, quick loops, and time editing remain available. Section looping is intended for listening and review; sample-accurate or gapless playback is not guaranteed.
