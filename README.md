# PolyHUB

Your Poly application workspace for Windows. Browse, launch and maintain PolyPDF, PolyWriter, PolySheet, PolyPhoto and PolyCAD. Every application also works independently.

## Download

Download the official [PolyHUB 0.2.1 setup](https://downloads.polystudio.tools/polyhub/0.2.1/PolyHUB-0.2.1-setup.exe) or [portable ZIP](https://downloads.polystudio.tools/polyhub/0.2.1/PolyHUB-0.2.1-win-x64.zip). Windows x64, Windows 10 build 19041 or newer / Windows 11. Self-contained packages include .NET; no separate runtime installation is needed.

- Setup: conventional installation for your Windows account, with optional desktop and Start menu shortcuts.
- Portable ZIP: extract the entire PolyHUB folder and run PolyHUB.exe. PolyHUB self-replacement requires a registered installation.

## Appearance

Use **Theme: Light / Theme: Dark** in the header to switch immediately. Settings also includes **Dark theme**. Your choice is saved and restored when PolyHUB starts.

## Actions and keyboard access

Application actions use vector icons with visible labels. Hover or focus an action for its explanation; disabled actions also keep tooltips. Use Tab to navigate and Enter/Space to activate focused buttons. F5 checks application releases. Header actions and card buttons wrap at smaller widths, and the five application cards remain available by scrolling. Light/dark themes apply to icons, text and focus outlines.

## Applications

PolyHUB checks each application's official per-user registration, installation marker, executable and version. Conflicting or incomplete registration is shown as Status unavailable and blocks maintenance. Portable application copies are not automatically adopted.

Release-check errors are shown separately from installation problems. A cached version is labelled last known and dated; it never enables an update after a failed check. Conflicting Windows/app-file versions are shown as unverified and maintenance stays blocked.

Open works offline. A failed release check does not mean that an app is absent or current. Install downloads and verifies the official setup, then opens its guided interface. Uninstall asks for confirmation and uses the application's official uninstaller. Close its windows and save your work first.

Managed updates require a version with PolyHUB integration: PolyPDF 0.1.3+, PolyWriter 0.1.2+, PolySheet 0.1.3+, PolyPhoto 0.1.1+, PolyCAD 0.0.6+. Earlier versions need a one-time update through their own About > Updates dialog. The application's own updater handles download controls, save prompts, differential/full packages and rollback. PolyHUB monitors its reported progress and independently verifies installed files before confirming success.

Only one PolyHUB maintenance operation runs at a time. If the process is interrupted, use Resume monitoring for a delegated update, or Review interrupted operation for an installer/uninstaller result. Stop monitoring pauses only PolyHUB observation; the application continues its own update and the operation remains recorded. Review checks the current state and does not repair or replace files. Keep application backup folders when recovery is needed.

## Update several applications

Choose **Check app updates**, then select **Include in update queue** on each eligible application, or use **Select available**. Choose **Update selected**, review installed and target versions, and choose **Start queue**. Applications run sequentially through their own updaters; finish any confirmation or save prompts in that application.

Before each handoff, PolyHUB checks the installation and official release again. Changed versions or packages, unavailable checks, cancellations, failures and unconfirmed results stop the queue. **Queue results** shows each outcome, including applications that were not started.

**Stop queue** stops monitoring and prevents the remaining applications from starting. An active application update may continue; use its own updater to cancel it. Resume monitoring or review a recorded operation before starting another. Queues are not saved or resumed automatically after restarting PolyHUB. Check app updates and select remaining applications again.

## Privacy and terms

Free to use. No required account, subscription, activation or telemetry. Release checks contact updates.polystudio.tools and downloads use downloads.polystudio.tools. Documents and photos are not uploaded. Update metadata is signed with trusted PolyStudio keys; exact package URLs, sizes and SHA-256 hashes are verified. Windows executable packages are not Authenticode-signed.

See LICENSE, THIRD-PARTY-NOTICES.txt and licenses/ for software terms and retained third-party and legacy MIT permissions. Private source and developer artifacts are not distributed.
PolyCAD requires PolyHUB 0.1.3+ and PolyCAD 0.0.6+ for delegated updates. Earlier PolyCAD versions remain detectable and launchable, with one-time integration guidance. CAD save prompts and recovery stay in PolyCAD.

PolyHUB 0.2.0 clients can receive the one-time 0.2.1 bridge through their existing updater. From 0.2.1 onward, PolyHUB and its application catalog check the signed PolyStudio channels without depending on GitHub API rate limits.
