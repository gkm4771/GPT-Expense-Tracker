OFFLINE EXPENSES TRACKER — DATA SAFETY RELEASE v4

Added: verified backup export digest record, backup age status, restore preview,
awaited receipt restore, local IndexedDB snapshots (daily, manual, before restore),
30-day cleanup for daily snapshots, database integrity checks, storage estimate,
and bounded change history for transaction/account/budget/recurring operations.

Retained: original interface, Google-Sheets-free offline mode, existing IndexedDB
financial database and receipts, financial tools, NAV refresh and existing reports.

NOT YET IMPLEMENTED OR FULLY VERIFIED: complete 32-item feature roadmap,
external automatic backups, detailed bank statement reconciliation, complete
audit of edits to separate assets/goals/loans arrays, native scheduled iOS
notifications, exhaustive financial accuracy and iPhone integration testing.

WARNING: Local snapshots share the same iPhone storage and do not replace
exported backups. Always export JSON to Files/iCloud Drive BEFORE upgrading.
Install on a test GitHub Pages path first, restore a backup and test offline.
Do not remove the working version until you verify all balances and receipts.
