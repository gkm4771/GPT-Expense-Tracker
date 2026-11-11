EXPENSES — OFFLINE ONLY (NO GOOGLE SHEETS)
This is a complete test build based on your uploaded index(2).html.

REMOVED: Google Sheets mode, Apps Script URL/key controls, Save and connect,
Import from Google Sheet, remote sheet fetch/post code, NAV Apps Script fallback.
Existing local data handling, transactions, budgets, assets, receipts, loans,
recurring items, backup and restore remain.

IMPORTANT:
1. Export a fresh full backup from the working app first.
2. Test this build on the SAME existing GitHub Pages origin/path only after
   backing up, or use a separate test deployment and restore your JSON.
3. The old Google Sheet mode is forcibly set to local mode, without importing
   anything from Sheets. This build NEVER migrates Sheets data automatically.
4. If installed at a different URL/path, restore your JSON backup manually.
5. Service worker cache is version v2. After uploading, launch online once,
   close/reopen, and test in Airplane Mode.
6. Mutual-fund NAV fetch from mfapi.in still requires internet.
7. Financial data remains in localStorage and receipts in IndexedDB;
   a future database migration needs independent validation.
8. Keep your original app and backup until records and offline operation are verified.
