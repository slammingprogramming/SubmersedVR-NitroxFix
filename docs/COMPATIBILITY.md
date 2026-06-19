# Compatibility

This page tracks the compatibility status of VR hardware, runtimes, and game configurations with SubmersedVR-NitroxFix.

The goal is to build a community-maintained compatibility database over time.

Legend:

| Status               | Meaning                                              |
| -------------------- | ---------------------------------------------------- |
| ✅ Confirmed Working  | Verified by developers or multiple community reports |
| 🟡 Partially Working | Works with limitations, bugs, or workarounds         |
| 🔵 Reported Working  | One or more user reports but not yet verified        |
| ❓ Untested           | No reliable testing data yet                         |
| ❌ Not Working        | Known incompatibility                                |

---

# VR Headset Compatibility

| Headset               | Status               | Motion Controllers | Multiplayer | Notes                      |
| --------------------- | -------------------- | ------------------ | ----------- | -------------------------- |
| Meta Quest 1          | 🔵 Reported Working  | 🟡 Mixed Reports   | ✅           | Community reports exist    |
| Meta Quest 2          | ❓ Untested           | ❓                  | ❓           | Testing needed             |
| Meta Quest 3          | 🟡 Partially Working | 🟡 Mixed Reports   | ✅           | Controller issues reported |
| Meta Quest Pro        | ❓ Untested           | ❓                  | ❓           | Testing needed             |
| Valve Index           | ❓ Untested           | ❓                  | ❓           | Testing needed             |
| HTC Vive              | ❓ Untested           | ❓                  | ❓           | Testing needed             |
| HTC Vive Pro          | ❓ Untested           | ❓                  | ❓           | Testing needed             |
| HTC Vive XR Elite     | ❓ Untested           | ❓                  | ❓           | Testing needed             |
| Windows Mixed Reality | ❓ Untested           | ❓                  | ❓           | Testing needed             |
| HP Reverb G2          | ❓ Untested           | ❓                  | ❓           | Testing needed             |
| Pimax Headsets        | ❓ Untested           | ❓                  | ❓           | Testing needed             |
| PSVR2 (PC Adapter)    | ❓ Untested           | ❓                  | ❓           | Testing needed             |

---

# Runtime Compatibility

| Runtime                 | Status              | Notes                |
| ----------------------- | ------------------- | -------------------- |
| SteamVR OpenXR          | ✅ Confirmed Working | Recommended runtime  |
| SteamVR OpenVR          | ✅ Confirmed Working | Required launch mode |
| Meta OpenXR Runtime     | ❓ Untested          | Testing needed       |
| Virtual Desktop Runtime | ❓ Untested          | Testing needed       |
| WMR OpenXR Runtime      | ❓ Untested          | Testing needed       |

---

# Connection Method Compatibility

| Connection Method | Status     | Notes                    |
| ----------------- | ---------- | ------------------------ |
| Steam Link        | ❓ Untested | Community testing needed |
| Quest Air Link    | ❓ Untested | Community testing needed |
| Virtual Desktop   | ❓ Untested | Community testing needed |
| Wired Link Cable  | ❓ Untested | Community testing needed |

---

# Storefront Compatibility

| Platform         | Status              | Notes                            |
| ---------------- | ------------------- | -------------------------------- |
| Steam            | ✅ Confirmed Working | Primary supported platform       |
| Epic Games Store | ❓ Untested          | Reports suggest issues may exist |
| Microsoft Store  | ❓ Untested          | No testing data                  |
| Game Pass        | ❓ Untested          | No testing data                  |

---

# Multiplayer Configuration Compatibility

| Configuration           | Status                | Notes                   |
| ----------------------- | --------------------- | ----------------------- |
| VR + VR                 | 🔵 Reported Working   | Community reports exist |
| VR + Flatscreen         | 🔵 Reported Working   | Community reports exist |
| Flatscreen + Flatscreen | ✅ Supported by Nitrox | Included for reference  |
| Dedicated Server        | ❓ Untested            | More testing needed     |
| Self Hosted Server      | 🔵 Reported Working   | Community reports exist |

---

# Controller Compatibility

| Controller Type          | Status              | Notes                      |
| ------------------------ | ------------------- | -------------------------- |
| Quest Motion Controllers | 🟡 Mixed Reports    | Some users report failures |
| Valve Index Controllers  | ❓ Untested          | Testing needed             |
| Vive Wands               | ❓ Untested          | Testing needed             |
| Xbox Controller          | 🔵 Reported Working | Common workaround          |
| PlayStation Controller   | ❓ Untested          | Testing needed             |
| Keyboard + Mouse         | 🔵 Reported Working | Community reports exist    |

---

# Special Setup Instructions

This section documents hardware-specific quirks, workarounds, and installation requirements.

---

## Meta Quest Headsets

### Recommended Configuration

* Steam version of Subnautica
* SteamVR running before launch
* Nitrox launch argument:

```text
-vrmode openvr
```

### OpenXR Runtime

If motion controllers do not function:

1. Open SteamVR Settings.
2. Navigate to OpenXR settings.
3. Set SteamVR as the active OpenXR Runtime.
4. Restart SteamVR.
5. Relaunch the game.

### Known Issues

* Quest 3 controller support is currently inconsistent.
* Some users report headset functionality while controller tracking fails.

---

## SteamVR Users

### Recommended Launch Order

1. Connect headset.
2. Start SteamVR.
3. Start Nitrox Launcher.
4. Launch the game through Nitrox.

Launching Nitrox before SteamVR may cause VR initialization problems on some systems.

---

## Meta Quest 3

### Current Status

Multiplayer VR is reported working.

Motion controller support has received mixed reports from users.

### Workarounds

If motion controls fail:

* Verify SteamVR is the active OpenXR runtime.
* Restart SteamVR.
* Try reconnecting the headset.
* Use an Xbox controller as a temporary workaround.

---

## Valve Index

### Status

Community testing needed.

Please report:

* Controller functionality
* Multiplayer stability
* Installation quirks
* Performance observations

---

## HTC Vive Family

### Status

Community testing needed.

Please report:

* Controller functionality
* Multiplayer stability
* Installation quirks
* Performance observations

---

## Windows Mixed Reality

### Status

Community testing needed.

Please report:

* OpenXR runtime used
* Controller functionality
* Multiplayer stability
* Installation quirks

---

# Contributing Compatibility Reports

When submitting a compatibility report, include:

* Headset model
* Controller type
* Runtime used
* Connection method
* Storefront version
* Nitrox version
* SubmersedVR version
* SubmersedVR-NitroxFix version
* Whether multiplayer worked
* Whether motion controls worked
* Any special setup steps required

Compatibility reports help improve this page for everyone.
