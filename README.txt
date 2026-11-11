EXPENSES OFFLINE IPHONE — INDEXEDDB UPGRADE (TEST)

This version uses IndexedDB for the financial ledger and imports your original
localStorage db automatically on first launch if no IndexedDB ledger exists.
The original localStorage db is kept as a recovery mirror when space allows.
Receipt photos remain in their existing IndexedDB store. All other app features
and the offline-only (no Google Sheets) design remain intact.

BEFORE INSTALLATION: Export a full JSON backup from the WORKING app and save it
outside the app (Files/iCloud Drive). Do not delete your original installation.

INSTALL: Replace the files in the SAME GitHub Pages deployment, open online,
close and reopen. Verify accounts, transaction counts, budgets, investments,
receipts, recurring transactions, loans and IOUs. Test airplane mode and a
new transaction, then force-close and relaunch to check persistence. Export
another full backup from the upgraded version.

IMPORTANT: On a different origin, restore your JSON backup manually. IndexedDB
and localStorage are both subject to iOS website-data eviction; neither is a
substitute for backups. If IndexedDB cannot open, the app uses its previous
localStorage fallback and displays a warning. NAV fetching still needs internet.
