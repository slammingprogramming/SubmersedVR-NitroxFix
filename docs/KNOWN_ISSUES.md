# Known Issues

This page documents currently known limitations and issues with SubmersedVR-NitroxFix.

Related docs: [Troubleshooting](TROUBLESHOOTING.md), [Compatibility](COMPATIBILITY.md), [FAQ](FAQ.md), [Installation](INSTALLATION.md)

Before opening a duplicate report, check whether your issue matches one of the entries below. New reproduction details, logs, and workaround notes are still useful.

## Quest 3 Motion Controllers May Not Function

**Status:** Under investigation. Testers and contributions welcome.

### Symptoms

- VR headset works correctly.
- Multiplayer functions normally.
- Quest controllers do not respond in-game.
- Xbox controller may still function.

### Workarounds

- Verify SteamVR is configured as the active OpenXR Runtime.
- Restart SteamVR after changing OpenXR settings.
- Use an Xbox controller as a temporary workaround.

### Related

- [Motion Controllers Not Working](TROUBLESHOOTING.md#motion-controllers-not-working)
- [Meta Quest Headsets](COMPATIBILITY.md#meta-quest-headsets)
- [Meta Quest 3](COMPATIBILITY.md#meta-quest-3)

## Intro Sequence May Cause Connection Problems

**Status:** Known. Contributions welcome.

### Symptoms

- Stuck during the Lifepod intro sequence.
- Infinite loading after joining a server.
- Client appears frozen during startup.

### Workarounds

- Enable Skip Cinematics on the Nitrox server.
- Reconnect if necessary.

### Related

- [Game Stuck During Startup](TROUBLESHOOTING.md#game-stuck-during-startup)

## Seamoth Ownership Issues

**Status:** Known. Contributions welcome.

### Symptoms

- Problems exiting a Seamoth owned by another player.
- Unexpected vehicle behavior.

### Workaround

Each player should build and use their own Seamoth. Avoid entering another player's Seamoth whenever possible.

## VR Hand Tracking Is Not Replicated

**Status:** Known limitation.

### Symptoms

- Motion controls function locally.
- Other players cannot see your tracked hand movements.

### Notes

This is a multiplayer synchronization limitation and is currently expected behavior.

## Storage Synchronization Issues

**Status:** In development. Contributions welcome.

### Symptoms

- Container contents may not synchronize correctly.
- Inventory interactions may occasionally behave unexpectedly.

### Notes

Improvements are actively being investigated.

## Base Synchronization Issues

**Status:** In development. Contributions welcome.

### Symptoms

- Certain base interactions may not synchronize correctly.
- Visual desynchronization may occur in some situations.

### Notes

Additional multiplayer synchronization improvements are planned.

## Steam Version Recommended

**Status:** Compatibility requirement.

### Notes

Current testing and community reports primarily use the Steam version of Subnautica.

Other storefront versions are currently unverified and may not function correctly. If you test another storefront, please submit a [compatibility report](../.github/ISSUE_TEMPLATE/compatibility_report.md).

## Reporting New Issues

When opening a [bug report](../.github/ISSUE_TEMPLATE/bug_report.md), include:

- Subnautica version.
- Nitrox version.
- SubmersedVR version.
- SubmersedVR-NitroxFix version.
- BepInEx version.
- SteamVR version.
- VR headset model.
- Controller type.
- BepInEx log files.
- Reproduction steps.
