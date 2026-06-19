# Frequently Asked Questions

Related docs: [Installation](INSTALLATION.md), [Compatibility](COMPATIBILITY.md), [Troubleshooting](TROUBLESHOOTING.md), [Known Issues](KNOWN_ISSUES.md)

## What Is SubmersedVR-NitroxFix?

SubmersedVR-NitroxFix is a compatibility bridge that allows Nitrox multiplayer and SubmersedVR to run together, enabling multiplayer Subnautica in VR.

## Do All Players Need VR?

No. VR and flatscreen players can play together on the same Nitrox server.

## Does This Work With Nitrox?

Yes. The mod was created specifically to bridge Nitrox and SubmersedVR. Nitrox 1.8.1 or newer is required.

## Does This Work With SubmersedVR?

Yes. SubmersedVR is required.

## Does This Work In Multiplayer?

Yes. Multiplayer is the primary purpose of the project.

## Does This Work With Quest Headsets?

Generally yes, but support varies by headset, runtime, and connection method. Quest users typically connect through SteamVR using Steam Link, Air Link, or Virtual Desktop.

See [Meta Quest Headsets](COMPATIBILITY.md#meta-quest-headsets) for current setup notes.

## Does This Work With Quest 3 Controllers?

Results are currently mixed. Some users report full functionality while others report controller input issues.

See [Quest 3 Motion Controllers May Not Function](KNOWN_ISSUES.md#quest-3-motion-controllers-may-not-function).

## Do I Need SteamVR?

Yes. SteamVR is currently required, and the recommended launch argument is:

```text
-vrmode openvr
```

See the [installation guide](INSTALLATION.md#step-6---configure-nitrox).

## Do I Need BepInEx?

Yes. BepInEx 5 must be installed before installing this project.

## Do I Need Nitrox?

Yes. Nitrox provides multiplayer functionality.

## Do I Need SubmersedVR?

Yes. SubmersedVR provides the VR functionality.

## Does This Work With The Epic Games Version?

Currently unverified. Most community testing has been performed using the Steam version of Subnautica.

If you test another storefront, please submit a [compatibility report](../.github/ISSUE_TEMPLATE/compatibility_report.md).

## Can I Play With An Xbox Controller?

Yes. Many users successfully play using an Xbox controller while using a VR headset.

## Can I Use VR Motion Controls?

Usually yes. However, some users have reported issues with Quest controller support.

See [Controller Compatibility](COMPATIBILITY.md#controller-compatibility).

## Can Flatscreen Players Join VR Players?

Yes. VR players and flatscreen players can connect to the same Nitrox server.

## Where Are Logs Stored?

Logs can be found at:

```text
BepInEx/LogOutput.log
```

You can also press `F11` in-game to generate a diagnostic snapshot.

## How Do I Report A Bug?

Use the [bug report template](../.github/ISSUE_TEMPLATE/bug_report.md) and include:

- Subnautica version.
- Nitrox version.
- SubmersedVR version.
- SubmersedVR-NitroxFix version.
- BepInEx version.
- SteamVR version.
- VR headset model.
- Controller type.
- BepInEx logs.
- Steps to reproduce the issue.
