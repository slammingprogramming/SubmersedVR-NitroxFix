# Known Issues

This page documents currently known limitations and issues with SubmersedVR-NitroxFix.

---

## Quest 3 Motion Controllers May Not Function

**Status:** Under Investigation, testers and contributions welcome!

### Symptoms

- VR headset works correctly
- Multiplayer functions normally
- Quest controllers do not respond in-game
- Xbox controller may still function

### Workarounds

- Verify SteamVR is configured as the active OpenXR Runtime
- Restart SteamVR after changing OpenXR settings
- Use an Xbox controller as a temporary workaround

### Root Cause

Currently unknown.

---

## Intro Sequence May Cause Connection Problems

**Status:** Known, contributions welcome!

### Symptoms

- Stuck during the Lifepod intro sequence
- Infinite loading after joining a server
- Client appears frozen during startup

### Workarounds

- Enable "Skip Cinematics" on the Nitrox server
- Reconnect if necessary

---

## Seamoth Ownership Issues

**Status:** Known, contributions welcome!

### Symptoms

- Problems exiting a Seamoth owned by another player
- Unexpected vehicle behavior

### Workaround

Each player should build and use their own Seamoth.

Avoid entering another player's Seamoth whenever possible.

---

## VR Hand Tracking Is Not Replicated

**Status:** Known Limitation, project for a later date.

### Symptoms

- Motion controls function locally
- Other players cannot see your tracked hand movements

### Notes

This is a multiplayer synchronization limitation and is currently expected behavior.

---

## Storage Synchronization Issues

**Status:** In Development, contributions welcome!

### Symptoms

- Container contents may not synchronize correctly
- Inventory interactions may occasionally behave unexpectedly

### Notes

Improvements are actively being investigated.

---

## Base Synchronization Issues

**Status:** In Development, contributions welcome!

### Symptoms

- Certain base interactions may not synchronize correctly
- Visual desynchronization may occur in some situations

### Notes

Additional multiplayer synchronization improvements are planned.

---

## Steam Version Recommended

**Status:** Compatibility Requirement, testers and contributions welcome!

### Notes

Current testing and community reports primarily use the Steam version of Subnautica.

Other storefront versions are currently unverified and may not function correctly.

---

## Reporting New Issues

When reporting a bug, please include:

- Subnautica version
- Nitrox version
- SubmersedVR version
- VR headset model
- SteamVR version
- BepInEx log files
- Reproduction steps