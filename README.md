# Local Focus downloads

Native macOS focus timer, activity tracker and distraction blocker.

[Download the latest release](https://github.com/VladislavKirpichov/local-focus-releases/releases/latest)

This repository distributes compiled app images, SHA-256 checksums and release notes.
Application source code is maintained in a separate private repository.

## Install

1. Download the DMG matching your Mac: `arm64` for Apple Silicon, `x86_64` for Intel.
2. Open the image and drag **Local Focus.app** to **Applications**.
3. Eject the image and launch the installed app.

Requires macOS 13 or newer. Current releases are ad hoc signed and are not notarized
by Apple. macOS may require approval in System Settings → Privacy & Security → Open Anyway.

## Updates

The app checks these public releases daily and offers a download when a compatible
newer version is available. Manual checks and automatic-check settings are in
Settings → General. Installation is manual. Quit the existing app before replacing
it; quitting ends the current session. History and settings are kept separately.

## Verify a download

Download the matching `.sha256` file next to the DMG and run:

```sh
shasum -a 256 -c Local-Focus-1.2.0-macOS-arm64.dmg.sha256
```

Use the filename for your downloaded version and architecture.
