PERSONAL EXPENSES TRACKER v5 — FINANCIAL ACCURACY TEST
Based on the user's v4 ZIP. No Google Sheets.
Changes: calendar date validation, transaction type validation, cross-currency
transfer received-amount validation, idempotence markers for generated loan
EMIs and recurring entries, checks against duplicate generated entries,
reconciliation numeric validation, zero-interest/invalid loan term safeguards.
Existing app UI and storage/backup code preserved.

Before replacing v4: Export a fresh verified backup.
Test with a separate GitHub Pages deployment and restored backup where possible.
If updating the same GitHub Pages site, install all files, open online once,
close/reopen to update service worker cache, then test offline.
Check transfers (same and cross currency), recurring payments, EMIs, investment
holdings, accounts, receipts, backups and balance reconciliation.
No automatic changes to existing transaction records.
NOT IMPLEMENTED HERE: full accounting audit, realized investment P/L, payment
processor synchronization, bank statement imports, or external notifications.
