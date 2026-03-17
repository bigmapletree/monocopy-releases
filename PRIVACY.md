# Privacy Policy

## Overview

MonoCopy is a cross-platform clipboard sync tool. We take your privacy seriously. This policy explains how the app handles your data.

## Data Collection & Storage

MonoCopy **does not collect or upload** any personal data. All data is stored locally on your device:

- Clipboard history is stored in local files
- Device pairing information and certificates are stored locally
- No cloud servers, third-party analytics, or advertising SDKs are used

## Network Communication

MonoCopy uses the network only in the following scenarios:

- **LAN Device Discovery**: Uses the mDNS protocol to discover other devices on your local network. No external servers are contacted
- **Device-to-Device Transfer**: Uses gRPC + mTLS encrypted protocol to transfer clipboard content and files between paired devices. All communication is end-to-end encrypted
- **Rich Media Download** (Desktop only): When you copy rich text containing external images, the app may download those images to preserve content integrity. This feature can be disabled in Settings

## Permissions

- **Clipboard Access**: Used to read and write clipboard content for cross-device sync
- **File Access**: Used for file transfer and history storage
- **Network Access**: Used for LAN device discovery and device communication

## Data Security

- Device communication uses mTLS (mutual TLS) encryption
- Device pairing uses X25519 key exchange protocol
- Transferred data is encrypted with AES-GCM

## Third-Party Services

MonoCopy does not use any third-party data collection, analytics, or advertising services.

## Contact

For privacy-related questions, please submit an issue on [GitHub](https://github.com/bigmapletree/monocopy-releases/issues).

*Last updated: March 2026*
