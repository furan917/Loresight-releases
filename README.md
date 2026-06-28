<p align="center">
  <img src="icon.png" alt="Loresight" width="128" height="128">
</p>

<h1 align="center">Loresight Releases</h1>

Loresight is a fully offline local-only companion for tabletop RPGs that I built to keep every quick reference I need at the table in one place. 

It's main purpose was to allow me to check up entities on the fly when I or a player speaks them (e.g spells/magic items) to save me stopping the game to look up what I forgot - instead the app would hear the spoken word and the tile would surface for me to click on if I needed it.  

It can also transcribe full sessions to a note. and you can browse/search every entity included in seconds. 

It runs **entirely** on your own device with no network, no
account and no server reachout, so nothing you do ever leaves your machine - it never saves audio either, the audio is immediately transcribed to text and discarded. For this reason the session transcripts cannot track who is who, it simply tracks that there is a new speaker within the same buffer window.

There is a full import functionality included too so that you can include your own legally owned content or add new TTRPG systems. Currently the systems included and their entities are just what is allowed by their respective licenses.

I built this as a base, the systems are not all encompassing and you will not find everything for the system in this application to avoid copyright issues.

This repository exists only to distribute downloadable builds of Loresight. There is no source code
here; the application is developed in a separate, private repository.

## Demo

<div align="center">

https://github.com/user-attachments/assets/2ee3da0a-fbad-4ea5-bbc6-603ed364708c

</div>

## Downloads

**➡️ [Download the latest version from the Releases page](https://github.com/furan917/Loresight-releases/releases)**

Then pick the file for your platform:

- Windows: `Loresight Setup <version>.exe`
- macOS: `Loresight-<version>.dmg`
- Linux: `Loresight-<version>.AppImage` (or the `.deb`)
- Android: `loresight-<version>.apk`

## Installing

The builds aren't code-signed yet, so each platform will warn you that the app is from an unidentified developer. That's expected. Here's how to get past it.

**Windows**

1. Run `Loresight Setup <version>.exe`.
2. If SmartScreen pops up, click **More info** then **Run anyway**.
3. Follow the installer.

**macOS**

1. Open the `.dmg` and drag Loresight into Applications.
2. The first time you launch it, right-click the app and choose **Open**, then confirm. A normal double-click will be blocked by Gatekeeper until you do this once.

**Linux**

AppImage:

1. Make it executable: `chmod +x Loresight-<version>.AppImage`
2. Run it: `./Loresight-<version>.AppImage`

Debian/Ubuntu (`.deb`):

1. `sudo dpkg -i loresight_<version>_amd64.deb`
2. If it complains about dependencies: `sudo apt-get install -f`

**Android**

1. Download the `.apk` to your device.
2. Open it. Android will ask you to allow installs from this source, so enable it for your browser or file manager.
3. Tap install.

Loresight is proprietary software. See `LICENSE`.
