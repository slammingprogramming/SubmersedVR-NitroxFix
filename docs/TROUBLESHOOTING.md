# Troubleshooting

This page covers common installation and startup issues.

If your issue is not listed, please open a GitHub issue and include your logs.

---

## Collecting Logs

Before reporting any issue:

1. Launch the game.
2. Reproduce the problem.
3. Press F11 if possible.
4. Locate:

BepInEx/LogOutput.log

Attach the log when requesting support.

---

## VR Starts in Flatscreen Mode

### Symptoms

- Game launches normally
- Headset remains inactive
- Game appears on monitor only

### Solutions

1. Verify SteamVR is running before launching Nitrox.
2. Open Nitrox Launcher.
3. Navigate to Options.
4. Verify launch arguments contain:

-vrmode openvr

5. Restart SteamVR and Nitrox.

---

## Game Stuck During Startup

### Symptoms

- Stuck at warning screen
- Infinite loading screen
- Client appears frozen

### Solutions

1. Verify all required components are installed.
2. Enable Skip Cinematics on the Nitrox server.
3. Restart SteamVR.
4. Verify all mods are updated.

If the problem persists, collect logs and report the issue.

---

## Motion Controllers Not Working

### Symptoms

- Headset works correctly
- Controllers do not respond

### Solutions

1. Verify SteamVR is set as the active OpenXR Runtime.
2. Restart SteamVR.
3. Restart the game.
4. Test controller functionality in another VR title.

If the issue persists, use an Xbox controller as a temporary workaround.

---

## Unable to Join a Server

### Symptoms

- Connection fails
- Join attempt times out

### Solutions

1. Verify Nitrox is functioning correctly without VR.
2. Verify the server is online.
3. Confirm all players use compatible versions.
4. Check firewall and antivirus settings.

---

## Missing Plugin

### Symptoms

- NitroxVRCompat does not load
- Plugin not listed in logs

### Solutions

Verify the following directory exists:

BepInEx/plugins/NitroxVrCompat/

Verify NitroxVrCompat.dll is present.

---

## Still Having Problems?

Please create a GitHub issue and include:

- Subnautica version
- Nitrox version
- SubmersedVR version
- VR headset model
- SteamVR version
- LogOutput.log
- Screenshots if applicable
- Reproduction steps