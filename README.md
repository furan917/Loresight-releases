<p align="center">
  <img src="icon.png" alt="Loresight" width="128" height="128">
</p>

<h1 align="center">Loresight</h1>

<p align="center">
  <strong>The rulebook that hears what your table says.</strong><br>
  A free, fully offline companion for tabletop RPGs.
</p>

<p align="center">
  <a href="https://furan917.github.io/Loresight-releases/">Website</a> ·
  <a href="https://play.google.com/store/apps/details?id=com.loresight.app">Google Play</a> ·
  <a href="https://github.com/furan917/Loresight-releases/releases">Desktop &amp; APK downloads</a> ·
  <a href="https://github.com/furan917/Loresight-releases/issues">Questions &amp; bug reports</a>
</p>

Loresight listens to the game, spots spells, monsters and items as they're spoken, and puts them one tap away so you stop flipping pages and keep the story moving. It can also transcribe a whole session into a saved note, and you can browse and search every entry in seconds.

It runs **entirely on your own device**: no network, no account, no server. Audio is transcribed to text the moment it's heard and then discarded, so nothing is ever recorded. Because of that, transcripts mark where the speaker changes rather than who is speaking.

**Loresight is free and will never be for sale.** If anyone asks you to pay for it, it is not Loresight. The only official downloads are Google Play and the Releases page of this repository.

This repository exists to distribute builds and host the website. There is no source code here; the app is developed in a separate private repository.

## What's inside

Four systems ship on day one, each limited to what its licence allows:

| System | Edition | Entries |
|---|---|---|
| Dungeons & Dragons 5e | SRD 5.1 | 1,193 |
| Dungeons & Dragons 5e (2024) | SRD 5.2 | 990 |
| Pathfinder 2e | Remaster (ORC) | 6,089 |
| Daggerheart | SRD 1.0 | 535 |

These are a base, not the whole game. You won't find everything for a system here, to stay clear of copyright.

**Bring your own content.** Every system is a content pack: one JSON file describing the game's structure and its entries. Import your homebrew, content you legally own, or an entirely new game, and it becomes browsable, searchable and spottable like everything else. The app's Import/Export screen has a built-in FAQ for authoring packs, and the [website](https://furan917.github.io/Loresight-releases/#import) walks through it too.

## Demo

<div align="center">

https://github.com/user-attachments/assets/2ee3da0a-fbad-4ea5-bbc6-603ed364708c

</div>

## Downloads

Android is the primary target and the best-tested build. Tablets, Windows, macOS and Linux are supported from the same codebase.

- **Android:** [Google Play](https://play.google.com/store/apps/details?id=com.loresight.app), or sideload `loresight-<version>.apk` from [Releases](https://github.com/furan917/Loresight-releases/releases)
- **Windows:** `Loresight Setup <version>-x64.exe`, or `-arm64.exe` for Windows on ARM
- **macOS:** `Loresight-<version>-x64.dmg`, or `-arm64.dmg` for Apple silicon
- **Linux:** `Loresight-<version>.AppImage` or the `.deb`, with `-arm64` / `_arm64` variants for ARM64 machines

## Installing

Loresight is a one-person project with no budget for the code-signing certificates Windows and Apple charge for, so each desktop platform will warn you that the app is from an unidentified developer. The app is exactly the same either way. Here's the one-time step for each platform.

**Windows**

1. Run `Loresight Setup <version>-x64.exe` (or the `-arm64` one on a Windows-on-ARM device).
2. If SmartScreen pops up, click **More info** then **Run anyway**.
3. Follow the installer.

**macOS**

1. Open the `.dmg` and drag Loresight into Applications.
2. The first time you launch it, right-click the app and choose **Open**, then confirm. A normal double-click is blocked by Gatekeeper until you've done this once.

**Linux**

AppImage:

1. Make it executable: `chmod +x Loresight-<version>.AppImage`
2. Run it: `./Loresight-<version>.AppImage`

Debian/Ubuntu (`.deb`):

1. `sudo dpkg -i loresight-desktop_<version>_amd64.deb`
2. If it complains about dependencies: `sudo apt-get install -f`

**Android (APK)**

1. Download the `.apk` to your device.
2. Open it. Android will ask you to allow installs from this source, so enable it for your browser or file manager.
3. Tap install.

## Privacy

Loresight works with networking switched off. Speech recognition runs on the device, audio is never written to disk, and your notes and imports live in a local database you can export at any time. See [PRIVACY.md](PRIVACY.md).

---

Loresight is proprietary software by [Furan917](https://github.com/furan917). See [LICENSE](LICENSE).
