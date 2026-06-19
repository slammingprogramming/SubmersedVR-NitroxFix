# Installation Guide

This guide walks through setting up Subnautica multiplayer in VR using Nitrox, SubmersedVR, and SubmersedVR-NitroxFix.

Related docs: [Compatibility](COMPATIBILITY.md), [Troubleshooting](TROUBLESHOOTING.md), [Known Issues](KNOWN_ISSUES.md), [FAQ](FAQ.md)

## Before You Start

Confirm that your setup matches the [requirements in the README](../README.md#requirements) and check the [compatibility database](COMPATIBILITY.md) for hardware, runtime, and storefront notes.

The Steam version of Subnautica is recommended because most testing has been done there.

## Step 1 - Install Subnautica

Install the Steam version of Subnautica and run it once before installing mods.

Other storefront versions are currently untested and may not work correctly. If you test one, please submit a [compatibility report](../.github/ISSUE_TEMPLATE/compatibility_report.md).

## Step 2 - Install BepInEx

Download BepInEx 5 and copy the `BepInEx` folder into your Subnautica installation directory.

Example layout:

```text
Subnautica/
|-- BepInEx/
|-- Subnautica.exe
```

## Step 3 - Install Nitrox

Install Nitrox 1.8.1 or newer.

Launch Nitrox once without VR to verify that the launcher starts correctly.

## Step 4 - Install SubmersedVR

Install SubmersedVR according to its own instructions.

Verify that VR works in singleplayer before proceeding. If VR launches in flatscreen mode later, see [VR Starts in Flatscreen Mode](TROUBLESHOOTING.md#vr-starts-in-flatscreen-mode).

## Step 5 - Install SubmersedVR-NitroxFix

Extract the SubmersedVR-NitroxFix release archive into your Subnautica installation folder.

The following files should be installed:

```text
BepInEx/plugins/NitroxVrCompat/
Subnautica_Data/Managed/Valve.Newtonsoft.Json.dll
```

If the plugin does not load, see [Missing Plugin](TROUBLESHOOTING.md#missing-plugin).

## Step 6 - Configure Nitrox

Open Nitrox Launcher, then navigate to:

```text
Options -> Subnautica Launch Arguments
```

Set:

```text
-vrmode openvr
```

Save and close the launcher.

## Step 7 - Launch VR Multiplayer

1. Connect your VR headset.
2. Start SteamVR.
3. Open Nitrox Launcher.
4. Click Launch Game.
5. Join or host a server.

Launching SteamVR before Nitrox is recommended. See [SteamVR Users](COMPATIBILITY.md#steamvr-users) for the expected launch order.

## Verify Installation

Successful installations should show:

- Nitrox loads successfully.
- SubmersedVR loads successfully.
- VR display or VR controllers function.
- Multiplayer server connection succeeds.
- `NitroxVRCompat` appears in the BepInEx logs.

## Diagnostic Logging

Press `F11` in-game to generate a diagnostic snapshot.

Logs are written to:

```text
BepInEx/LogOutput.log
```

Include this file when opening a [bug report](../.github/ISSUE_TEMPLATE/bug_report.md).
