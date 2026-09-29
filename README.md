# RCV Launcher

**RCV Launcher** is the official RCV Android launcher for Minecraft: Java Edition.

- Full-version Minecraft: Java Edition support on Android, including the latest snapshots
- Loader support: Fabric, Forge, NeoForge, Quilt, LegacyFabric, Cleanroom, OptiFine
- Bundled Java runtimes (Java 8 / 17 / 21 / 25) with automatic recommendation and manual override
- Pluggable renderer system (Holy GL4ES, VirGL, VGPU, Zink/Mesa, Freedreno, NG-GL4ES + renderer plugins)
- Virtual mouse, custom touch controls, gamepad support, control layout import/export
- Mod, modpack, resource pack, shader pack and world management (Modrinth integration)
- Built-in RCV update system with SHA-256 verified downloads
- Modern dark UI tuned for performance on low-end devices

## Requirements

- Android 8.0 (API 26) or newer
- arm64-v8a device (per-release variants may add other architectures)

## Installation

1. Download the latest APK from the [Releases](../../releases) page.
2. Verify the published SHA-256 if you wish (listed in each release and in `release.json`).
3. Install the APK. On first launch, RCV Launcher asks for the storage access it needs to manage game files.

## Downloads

- **Stable releases:** published as regular GitHub Releases (`vX.Y.Z`)
- **Development builds:** published as pre-releases (`vX.Y.Z-dev.N`) and marked *Development Build*

Every release ships `release.json` with the exact version, versionCode, SHA-256 and changelog used by the built-in updater.

## Support

Use the GitHub issue tracker for bug reports and feature requests.

## Legal

RCV Launcher is distributed under the **GNU GPL-3.0** license (see [LICENSE](LICENSE)).

RCV Launcher branding, UI, services, assets, integrations, and RCV-specific modifications are maintained by RCV. Legally required open-source notices for the projects RCV Launcher is based on are provided separately — see the in-app **Settings → About → Open Source Licenses** page and the license files in this repository.

RCV Launcher is not affiliated with Mojang Studios or Microsoft. Minecraft is a trademark of Mojang Synergies AB.

Copyright © RCV
