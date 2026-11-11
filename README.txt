EXPENSES OFFLINE IPHONE PWA — TEST BUILD

This package includes your uploaded index(2).html, not a re-created UI.
The source already includes a service-worker registration. This package adds
the matching service worker, manifest and app icons.

CHANGES:
- New installations default to 'This iPhone only' mode.
- Existing installations preserve their chosen storage mode.
- All app files needed for launching are cached after the first online visit.
- Existing localStorage ledger, receipt IndexedDB, and backup/restore code remain unchanged.

INSTALL:
1. Back up your current app using Settings > Back up to Files.
2. Create a separate TEST GitHub Pages repository or deployment path.
3. Upload the SIX files in this ZIP at the root of that deployment.
4. Open the HTTPS page in iPhone Safari while online.
5. In Safari: Share > Add to Home Screen. Launch the new icon while online.
6. In the new app Settings, confirm 'This iPhone only' mode.
7. Restore the JSON backup using 'Restore from backup file'.
8. Check account balances, transaction counts, investments, budgets,
   recurring items, loans, IOUs, and receipt attachments.
9. Test with Airplane Mode on, force-close, reopen, add a test transaction,
   edit it, export a backup, and verify the changes after relaunch.

CAUTIONS:
- Storage is isolated by origin and installation; your original app's data
  does not automatically appear in this test build.
- This build retains localStorage for financial records. A move to IndexedDB
  requires separate migration/testing to avoid ledger corruption.
- NAV updates and external APIs require internet.
- Do not delete original hosting or original app until backup restore and
  offline tests succeed. Removing hosting risks future reinstallation.
- PWA storage/cache may be evicted by iOS. Export backups regularly.
