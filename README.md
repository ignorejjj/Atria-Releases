# Atria downloads

This repository distributes Atria installers and public update metadata. Application development remains in a separate private repository; no development checkout or user data belongs here.

- [Download releases](https://github.com/ignorejjj/Atria-Releases/releases)
- [Runtime components and corresponding third-party source materials](https://github.com/ignorejjj/Atria-Components/releases/tag/components-v1)

The current beta targets Apple Silicon Macs with macOS 14 or later. Its ad-hoc signature is not an Apple Developer ID and it is not notarized. Use the normal macOS approval flow if required; do not disable system security. The CLI requires Node.js 22.19.0 or later and npm.

Installers include license notices and required bundled third-party materials. Verify the SHA-256 checksum before manual installation.

The App reads `updates/latest.json` anonymously. Each listed installer is bound to a fixed release tag, exact file name, size and SHA-256. Updates are downloaded and installed only after the user requests them.
