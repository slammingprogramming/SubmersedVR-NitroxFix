# Installation Guide

This guide walks through setting up Subnautica multiplayer in VR using Nitrox and SubmersedVR.

## Step 1 - Install Subnautica

Install the Steam version of Subnautica.

Other storefront versions are currently untested and may not work correctly.

## Step 2 - Install BepInEx

Download BepInEx for Subnautica.

Extract the archive and copy the `BepInEx` folder into your Subnautica installation directory.

Example:

Subnautica/
├─ BepInEx/
├─ Subnautica.exe

## Step 3 - Install Nitrox

Install the latest Nitrox release.

Launch Nitrox once to verify it starts correctly.

## Step 4 - Install SubmersedVR

Install SubmersedVR according to its instructions.

Verify that VR works in singleplayer before proceeding.

## Step 5 - Install SubmersedVR-NitroxFix

Extract the release archive into your Subnautica installation folder.

The following files should be installed:

BepInEx/plugins/NitroxVrCompat/

Subnautica_Data/Managed/Valve.Newtonsoft.Json.dll

## Step 6 - Configure Nitrox

Open Nitrox Launcher.

Navigate to:

Options → Subnautica Launch Arguments

Set:

-vrmode openvr

Save and close the launcher.

## Step 7 - Launch VR Multiplayer

1. Connect your VR headset.
2. Start SteamVR.
3. Open Nitrox Launcher.
4. Click Launch Game.
5. Join or host a server.

## Verify Installation

Successful installations should show:

* Nitrox loads successfully
* SubmersedVR loads successfully
* VR controllers or VR display function
* Multiplayer server connection succeeds

## Diagnostic Logging

Press F11 in-game.

Logs will be written to:

BepInEx/LogOutput.log

Include this file when reporting issues.