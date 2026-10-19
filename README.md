# SolArchitect

No-code desktop app for creating Solana tokens. Non-custodial: your private keys never leave your device.

Website: https://solarchitect.xyz
X/Twitter: https://x.com/SolArchitectxyz

> This repository hosts release information, checksums and issue tracking. The application source code is not published here.

## What it is

SolArchitect lets you create a Solana token through a simple interface, with no code and no command line. It runs on your own computer and opens in your default browser, so your existing wallet extension works as usual.

## Features

- Token standards: SPL and Token-2022
- Metaplex metadata
- Three-tier metadata storage: Arweave, then IPFS, then local cache as a fallback
- Wallets: Phantom, Solflare, Backpack
- 13 interface languages
- Platforms: Windows, macOS, Linux
- Non-custodial: transactions are signed in your wallet, keys stay on your device

## Pricing

| Plan | Price | What you get |
|---|---|---|
| Desktop App License | $99, one-time | The desktop app for Windows, macOS and Linux |
| Developer Package | $299, one-time | Source code and all builds |

There is no per-transaction platform fee. Network fees of the Solana blockchain still apply when you create a token.

## Download

The app is available after purchase at https://solarchitect.xyz. Each buyer receives a personal download link by email.

The installers themselves are not published in this repository. The [Releases](../../releases) page contains only release notes and SHA-256 checksums for each version, so you can verify the file you received.

## Verify your download

Each release lists a SHA-256 checksum for every file. Compare it with the checksum of the file you downloaded from your personal link.

macOS:

```
shasum -a 256 SolArchitect-<version>.dmg
```

Linux:

```
sha256sum SolArchitect-<version>.AppImage
```

Windows (PowerShell):

```
Get-FileHash .\SolArchitect-<version>.exe -Algorithm SHA256
```

If the result does not match the checksum in the release notes, do not run the file and contact us.

## Checksums

| File | SHA-256 |
|---|---|
| SolArchitect-<version>-windows.exe | `<sha256>` |
| SolArchitect-<version>-macos.dmg | `<sha256>` |
| SolArchitect-<version>-linux.AppImage | `<sha256>` |

## Security warnings from your operating system

Current builds are not yet code-signed with a paid developer certificate. Because of this, Windows SmartScreen or macOS Gatekeeper may show a warning on first launch. Check the checksum above before you proceed. Code signing is planned.

## Support and bug reports

- Bugs and feature requests: open an issue in this repository
- Questions: faq@solarchitect.xyz
- Sales: sales@solarchitect.xyz

## Disclaimer

SolArchitect is a software tool. It is not financial or legal advice, and it does not promise any profit from the tokens you create. Token creation and distribution may be regulated in your country. You are responsible for complying with local laws.
