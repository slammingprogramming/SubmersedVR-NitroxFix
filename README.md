# SubmersedVR-NitroxFix

SubmersedVR-NitroxFix is a compatibility bridge between [Nitrox Multiplayer](https://nitrox.rux.gg/) and [SubmersedVR](https://github.com/Okabintaro/SubmersedVR), allowing Subnautica multiplayer sessions to run in VR.

The project ships as the `NitroxVRCompat` BepInEx plugin and includes a basic diver avatar plus contextual player animation support for multiplayer VR sessions.

Created by Connor and Zach (Geeks and Me LLC).

## Features

- Play Nitrox multiplayer in VR.
- Join the same server with VR and flatscreen players.
- Use a diver body representation for multiplayer presence.
- Enable contextual player animations.
- Generate diagnostic logs for troubleshooting.

## Requirements

Before installing, make sure these are available:

- Subnautica 2025 Patch, Steam version recommended.
- [BepInEx 5](https://github.com/BepInEx/BepInEx).
- Nitrox 1.8.1 or newer.
- SubmersedVR 0.2.0.
- SteamVR.

For tested hardware, runtimes, and storefronts, see the [compatibility database](docs/COMPATIBILITY.md).

## Documentation

- [Docs Home](docs/README.md) - start here for setup and support paths.
- [Installation Guide](docs/INSTALLATION.md) - install BepInEx, Nitrox, SubmersedVR, and this plugin.
- [Compatibility](docs/COMPATIBILITY.md) - headset, runtime, storefront, and controller status.
- [Troubleshooting](docs/TROUBLESHOOTING.md) - common startup, VR, controller, and connection problems.
- [Known Issues](docs/KNOWN_ISSUES.md) - current limitations and recommended workarounds.
- [FAQ](docs/FAQ.md) - quick answers for common questions.

## Download

Download the latest packaged build from the repository's [Releases](../../releases) page.

## Quick Start

1. Install the required dependencies listed above.
2. Follow the [installation guide](docs/INSTALLATION.md).
3. Start SteamVR before launching the game.
4. Launch Subnautica through Nitrox Launcher.
5. Join or host a Nitrox server.

## Diagnostics

Press `F11` in-game to generate a diagnostic snapshot. Logs are written to:

```text
BepInEx/LogOutput.log
```

The hotkey can be changed in:

```text
BepInEx/config/com.csore.nitroxvrcompat.cfg
```

## Support And Reports

Before opening an issue, check:

- [Known Issues](docs/KNOWN_ISSUES.md)
- [Troubleshooting](docs/TROUBLESHOOTING.md)
- [FAQ](docs/FAQ.md)
- [Compatibility](docs/COMPATIBILITY.md)

When reporting bugs, include your Subnautica, Nitrox, SubmersedVR, BepInEx, SteamVR, headset, controller, and log details. Use the repository's [issue templates](../../issues/new/choose) so maintainers get the information they need.

## Contributing

Compatibility reports, docs fixes, repro steps, and source contributions are welcome. Start with [CONTRIBUTING.md](CONTRIBUTING.md), then open the issue or pull request that best matches the change.
