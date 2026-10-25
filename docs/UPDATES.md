# Updates

About > Updates provides manual checks, optional startup checks, release notes, progress, download cancellation, retry, the last update result and Manage update storage. A newer release also appears in the header. Application release checks have a separate startup preference in Settings.

PolyHUB updates only itself through robertmartic/polyhub. Application updates use each application's independent official channel and existing updater through the supported local connection. Old app versions require a one-time upgrade in their own About > Updates dialog. Unsaved work stays under that application's Save / Don't save / Cancel decisions.

PolyHUB verifies HTTPS release origins and SHA-256 package/file hashes. Matching file-level deltas contain complete changed files; an unavailable or modified base uses the full-package fallback. Version 0.1.2 includes a file-level delta from the 0.1.0 baseline. Modified or unmatched installations use the full package. Hash checks trust the official release account/service and are not Authenticode signatures.

A separate helper stages and verifies the self-update, replaces the application while closed, refreshes registration through the maintenance installer and rolls back handled replacement/registration failures. Backup folders are retained. Restart failure is distinguished from installation failure. After a confirmed successful restart the embedded Changelog opens once.

PolyHUB does not replace or close itself while it is supervising maintenance. Downloads may be cancelled; once a guided installer or application updater owns the operation, use that application's controls. An interrupted or unconfirmed operation remains recorded for review.

Storage cleanup is explicit and preserves active/prepared jobs, protected backups and unrelated data. Failed staging or unrecognised folders remain for manual review. User settings, documents and recovery data are outside cleanup. After a forced termination or power loss, retain backups and use the official full installer for recovery when needed.
