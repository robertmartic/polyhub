# PolyHUB

Your Poly application workspace for Windows. Browse, launch and maintain PolyPDF, PolyWriter, PolySheet and PolyPhoto. Every application also works independently.

## Download

Use the official [GitHub releases](https://github.com/robertmartic/polyhub/releases). Windows x64, Windows 10 build 19041 or newer / Windows 11. Self-contained packages include .NET; no separate runtime installation is needed.

- Setup: conventional installation for your Windows account, with optional desktop and Start menu shortcuts.
- Portable ZIP: extract the entire PolyHUB folder and run PolyHUB.exe. PolyHUB self-replacement requires a registered installation.

## Appearance

Use **Theme: Light / Theme: Dark** in the header to switch immediately. Settings also includes **Dark theme**. Your choice is saved and restored when PolyHUB starts.

## Applications

PolyHUB checks each application's official per-user registration, installation marker, executable and version. Conflicting or incomplete registration is shown as Status unavailable and blocks maintenance. Portable application copies are not automatically adopted.

Release-check errors are shown separately from installation problems. A cached version is labelled last known and dated; it never enables an update after a failed check. Conflicting Windows/app-file versions are shown as unverified and maintenance stays blocked.

Open works offline. A failed release check does not mean that an app is absent or current. Install downloads and verifies the official setup, then opens its guided interface. Uninstall asks for confirmation and uses the application's official uninstaller. Close its windows and save your work first.

Managed updates require a version with PolyHUB integration: PolyPDF 0.1.3+, PolyWriter 0.1.2+, PolySheet 0.1.3+, PolyPhoto 0.1.1+. Earlier versions need a one-time update through their own About > Updates dialog. The application's own updater handles download controls, save prompts, differential/full packages and rollback. PolyHUB monitors its reported progress and independently verifies installed files before confirming success.

Only one PolyHUB maintenance operation runs at a time. If the process is interrupted, use Resume monitoring for a delegated update, or Review interrupted operation for an installer/uninstaller result. Stop monitoring pauses only PolyHUB observation; the application continues its own update and the operation remains recorded. Review checks the current state and does not repair or replace files. Keep application backup folders when recovery is needed.

## Privacy and terms

Free to use. No required account, subscription, activation or telemetry. Release checks and downloads contact the official GitHub channels. Documents and photos are not uploaded. SHA-256 checks integrity using the official GitHub release digests; it is not a separate digital signature. Packages are not code-signed.

See LICENSE, THIRD-PARTY-NOTICES.txt and licenses/ for software terms and retained third-party and legacy MIT permissions. Private source and developer artifacts are not distributed.
