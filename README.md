# GDC Tools releases

Version metadata for the GDC Tools / ACC Batch Script Runner Revit add-in.
The add-in reads `latest.json` (at most once a week) to announce new versions
and to extend the built-in validity date.

- `latestVersion` — newest released version; the add-in notifies when it is newer than the installed one.
- `downloadNote` — shown in the update notification.
- `allowedUntil` — ISO date; extends the build's compiled-in expiry when later.
- `minVersion` — optional kill switch (reserved).
- `message` — optional extra text shown in notifications/expiry dialogs.
