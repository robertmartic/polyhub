# Updates

About > Updates provides manual checks, optional startup checks, release notes, progress, download cancellation, retry, the last update result and Manage update storage. A newer release also appears in the header. Application release checks have a separate startup preference in Settings.

PolyHUB updates only itself through the signed updates.polystudio.tools/polyhub/stable.json channel. Application updates use each application's independent official channel and existing updater through the supported local connection. Old app versions require a one-time upgrade in their own About > Updates dialog. Unsaved work stays under that application's Save / Don't save / Cancel decisions.

PolyHUB verifies HTTPS release origins and SHA-256 package/file hashes. Matching file-level deltas contain complete changed files; an unavailable or modified base uses the full-package fallback. Version 0.2.1 includes a file-level delta from the 0.2.0 baseline. Modified or unmatched installations use the full package. Signed metadata is verified using embedded PolyStudio public keys. Metadata and downloads use exact HTTPS paths without redirects; package sizes and SHA-256 hashes must match. Windows executable packages are not Authenticode-signed.

A separate helper stages and verifies the self-update, replaces the application while closed, refreshes registration through the maintenance installer and rolls back handled replacement/registration failures. Backup folders are retained. Restart failure is distinguished from installation failure. After a confirmed successful restart the embedded Changelog opens once.

PolyHUB does not replace or close itself while it is supervising maintenance. Downloads may be cancelled; once a guided installer or application updater owns the operation, use that application's controls. An interrupted or unconfirmed operation remains recorded for review.

Storage cleanup is explicit and preserves active/prepared jobs, protected backups and unrelated data. Failed staging or unrecognised folders remain for manual review. User settings, documents and recovery data are outside cleanup. After a forced termination or power loss, retain backups and use the official full installer for recovery when needed.


For multiple application updates, use the selection controls and Update selected in the main window. The review lists exact target versions. Each application must finish with an independently verified result before the next starts. A changed installation/release, failed check, cancellation, failure or unconfirmed result stops the queue. Stop queue stops observation and prevents remaining handoffs; the active application may continue. Queue results remain available in the current session. Only the active operation is recorded for monitoring/review after a restart; remaining selections never run automatically.

Application release checks use each application's signed stable channel at updates.polystudio.tools. Fresh installation uses the setup URL declared in that signed channel at downloads.polystudio.tools. Installed-app updates continue through each application's own supported local connection and retain its save and update protections. The 0.2.1 GitHub release is a one-time bridge for older PolyHUB clients; normal checks from 0.2.1 do not use the GitHub API.
