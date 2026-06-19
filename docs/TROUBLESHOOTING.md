# Troubleshooting

This page covers common installation, startup, VR, controller, and multiplayer issues.

Related docs: [Installation](INSTALLATION.md), [Compatibility](COMPATIBILITY.md), [Known Issues](KNOWN_ISSUES.md), [FAQ](FAQ.md)

If your issue is already listed in [Known Issues](KNOWN_ISSUES.md), use the existing workaround when possible and include any new details in your report.

## Collecting Logs

Before reporting any issue:

1. Launch the game.
2. Reproduce the problem.
3. Press `F11` if possible.
4. Locate the log file:

```text
BepInEx/LogOutput.log
```

Attach the log when opening a [bug report](../.github/ISSUE_TEMPLATE/bug_report.md).

## VR Starts In Flatscreen Mode

### Symptoms

- Game launches normally.
- Headset remains inactive.
- Game appears on the monitor only.

### Solutions

1. Verify SteamVR is running before launching Nitrox.
2. Open Nitrox Launcher.
3. Navigate to `Options`.
4. Confirm launch arguments contain:

```text
-vrmode openvr
```

5. Restart SteamVR and Nitrox.

For the recommended launch order, see [SteamVR Users](COMPATIBILITY.md#steamvr-users).

## Game Stuck During Startup

### Symptoms

- Stuck at the warning screen.
- Infinite loading screen.
- Client appears frozen.

### Solutions

1. Verify all required components are installed.
2. Enable Skip Cinematics on the Nitrox server.
3. Restart SteamVR.
4. Verify all mods are updated.

This may overlap with [Intro Sequence May Cause Connection Problems](KNOWN_ISSUES.md#intro-sequence-may-cause-connection-problems).

## Motion Controllers Not Working

### Symptoms

- Headset works correctly.
- Controllers do not respond.

### Solutions

1. Verify SteamVR is set as the active OpenXR Runtime.
2. Restart SteamVR.
3. Restart the game.
4. Test controller functionality in another VR title.

If the issue persists, use an Xbox controller as a temporary workaround and check [Quest 3 Motion Controllers May Not Function](KNOWN_ISSUES.md#quest-3-motion-controllers-may-not-function).

## Unable To Join A Server

### Symptoms

- Connection fails.
- Join attempt times out.

### Solutions

1. Verify Nitrox works without VR.
2. Verify the server is online.
3. Confirm all players use compatible versions.
4. Check firewall and antivirus settings.

If only VR clients are affected, include headset, runtime, and connection method details in your [bug report](../.github/ISSUE_TEMPLATE/bug_report.md).

## Missing Plugin

### Symptoms

- `NitroxVRCompat` does not load.
- Plugin is not listed in logs.

### Solutions

Verify the following directory exists:

```text
BepInEx/plugins/NitroxVrCompat/
```

Verify `NitroxVrCompat.dll` is present in that directory.

## Still Having Problems?

Please open a [bug report](../.github/ISSUE_TEMPLATE/bug_report.md) and include:

- Subnautica version.
- Nitrox version.
- SubmersedVR version.
- SubmersedVR-NitroxFix version.
- BepInEx version.
- SteamVR version.
- VR headset model.
- Controller type.
- `LogOutput.log`.
- Screenshots if applicable.
- Reproduction steps.
