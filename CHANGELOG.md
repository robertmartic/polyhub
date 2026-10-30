# Changelog

## 0.2.1

- PolyHUB and application release checks now use signed official PolyStudio update channels.
- Application installation packages come from the official PolyStudio download server.
- Update information and downloads are verified against trusted signing keys, exact application/version identities, package sizes and SHA-256 hashes.
- Application save prompts, sequential update queues and interrupted-operation monitoring remain available.

## 0.2.0

- Select several applications with available updates, review their target versions, and update them one at a time.
- Each application keeps its own updater, download controls and document save prompts.
- The queue rechecks installation and official release identities before each update, and stops on cancellation, failure or an unconfirmed result.
- Stop queue prevents remaining updates and stops monitoring; an active application update can continue and remains available for monitoring or review.
- Review per-application results from the last queue. Remaining applications require a new selection; queues never restart automatically.

## 0.1.4
- Add clear vector icons beside application actions while keeping Open, Install, Update, Uninstall and Update help labels visible.
- Add matching icons and tooltips to header and maintenance controls.
- Improve keyboard focus, accessible action names, disabled-state explanations and light/dark contrast.
- Keep actions readable at narrow window sizes with wrapping layouts; all five app cards remain accessible.
- Check application releases with F5.

## 0.1.3
- Add PolyCAD to the application catalog with its owner-provided logo.
- Discover and launch registered PolyCAD installations and offer official install/uninstall actions.
- Delegate updates to PolyCAD 0.0.6+ while preserving its save prompts and recovery protections.
- Show one-time upgrade guidance for older PolyCAD versions.
- Extend the application grid to three rows so all five cards remain accessible.

## 0.1.2

- Switch between light and dark themes using the visible Theme button in the header or Settings. The choice is remembered.
- Distinguish installed versions, unverified registration, unavailable release checks and last-known release information.
- Show release-check times and clear one-time update guidance for older Poly applications.
- Stop and resume update monitoring without cancelling the application's own update or losing its recorded state.
- Keep uncertain update handoffs recorded and prevent installer operations from resuming as update monitors.
- Improve dark-theme readability in Settings and show the current release notes in About.

## 0.1.0

- Initial PolyHUB release with application discovery, guided installation and uninstall, coordinated application updates and its own updater.
- Light and dark themes, local settings and verified operation results.
