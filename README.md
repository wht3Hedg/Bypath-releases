# Bypath-releases

A client for Windows and Android built on [Xray-core](https://github.com/XTLS/Xray-core).

|  Platform  |  Version  | Download |
|------------|-----------|----------|
| Windows 10+, x64 | 1.4.1 | [Bypath-1.4.1.msi](../../releases/tag/v1.4.1) |
| Android 8.0+, arm64 | 1.1.0 | [Bypath-1.1.0.apk](../../releases/tag/android-v.1.1.0) |

All releases: [Releases](../../releases)

## Features

- VLESS (REALITY / TLS), Trojan, Shadowsocks, Hysteria2; subscription links.
- Per-app and per-site routing, ready-made domain sets, ad blocking.
- Automatic fallback between profiles and servers.
- Selected apps are cut off if the server connection drops; DNS follows the routing rules.
- Self-check and a live connection log.

## Privacy

No telemetry, no accounts. Links and subscriptions are stored only on your computer, encrypted with Windows DPAPI.

## Install

1. Download `Bypath-<version>.msi` from the [latest release](../../releases/latest).
2. Verify the checksum against the one in the release notes. Open the folder with the downloaded file, click the address bar, type `powershell` and press Enter. In the PowerShell window run, replacing `<version>` with the version you downloaded:
   ```powershell
   Get-FileHash .\Bypath-<version>.msi
   ```
If the `Hash` value does not match, do not install.
3. Run the installer. It is not code-signed, so SmartScreen may warn you: "More info" → "Run anyway".

## Disclaimer

Bypath is a client application only. It does not include any servers and does not offer server access or any paid services. Users are responsible for obtaining or setting up their own servers and for complying with the laws applicable in their jurisdiction when using the app.

## Issues

Report problems in [Issues](../../issues). Never attach links, subscriptions or screenshots showing your server address.
