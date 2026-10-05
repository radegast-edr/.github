# Radegast EDR GitHub Organization

Welcome to the Radegast EDR GitHub organization. Radegast is an open-source endpoint detection and response platform built for secure, privacy-first telemetry and threat detection.

## About the organization

Radegast EDR focuses on transparent, community-driven threat detection with end-to-end encrypted telemetry. The organization hosts the endpoint detection engine, rule packs, agent, console, and web repositories that together power the Radegast ecosystem.

## Quickstart

- [Screenhost](https://radegast.app/screenshots/)
- [Using Radegast](https://docs.radegast.app/quickstart)
- [Selfhosting](https://docs.radegast.app/README)

## Published repositories

### Management Console & Backend
- [radegast-console-web](https://github.com/radegast-edr/radegast-console-web) -- Browser-based web console frontend built with SvelteKit and Bootstrap for managing devices, inspecting alerts, and exploring endpoint telemetry.
- [radegast-console-backend](https://github.com/radegast-edr/radegast-console-backend) -- Backend API and service layer powering the Radegast Console, handling authentication, data flows, and console operations with end-to-end encryption.

### Endpoint & Detection Engine
- [rustinel](https://github.com/radegast-edr/rustinel) -- Fork of [Karib0u/rustinel](https://github.com/Karib0u/rustinel); open-source cross-platform endpoint detection engine for Windows, macOS, and Linux.
- [radegast-agent-python](https://github.com/radegast-edr/radegast-agent-python) -- Python-based Radegast agent wrapper for Rustinel, syncing detection packs and forwarding encrypted alerts to the backend.
- [radegast-rustinel-updater](https://github.com/radegast-edr/radegast-rustinel-updater) -- Secure auto-updater service for the Radegast Rustinel EDR sensor with cryptographic signature verification.

### Detection Content & Rules
- [radegast-packages](https://github.com/radegast-edr/radegast-packages) -- Bundled detection packages and packaging utilities structured by operating system and coverage levels for the Radegast platform.

### Web & Organization
- [radegast-web](https://github.com/radegast-edr/radegast-web) -- Landing page and official project website ([radegast.app](https://radegast.app)).
- [.github](https://github.com/radegast-edr/.github) -- Organization-level profile configuration and community health resources.

## Organization purpose

Radegast EDR aims to provide:

- Open-source endpoint detection and response tooling
- Privacy-first data handling with end-to-end encryption
- An easy-to-use console for alert visibility and device management
- Easy deployment via open agents and community detection rules

## Project websites

- Main site: https://radegast.app
- Docs: https://docs.radegast.app/
- Console: https://console.radegast.app
- Org page: https://github.com/radegast-edr

## Contributing

If you want to contribute, open issues or pull requests in the repository most relevant to your change:

- Detection engine: `rustinel` (fork of [Karib0u/rustinel](https://github.com/Karib0u/rustinel))
- Detection rules and content: `rustinel-rules` (fork of [Karib0u/rustinel-rules](https://github.com/Karib0u/rustinel-rules)) or `radegast-packages`
- Agent & sensor updater: `radegast-agent-python` or `radegast-rustinel-updater`
- UI/console changes: `radegast-console-web`
- Backend/API changes: `radegast-console-backend`
- Website content or marketing updates: `radegast-web`

## License

Repositories in this organization are primarily licensed under Apache 2.0. Please refer to each repository's `LICENSE` file for details.
