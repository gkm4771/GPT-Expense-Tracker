Expenses Tracker v6 — Investment Insights TEST

Built from v5. No backend, no Google Sheets. Existing IndexedDB schema unchanged.

New visible features:
- Investments: OMR and INR separate summaries for invested cost, current value, value change, percentage, and allocation by asset type.
- Credit cards: available credit and over-limit label (when credit limit set).
- Settings: v6 info card.
- Fix: due-loan alert recording used an undefined variable; now records the correct due date.
- Recurring bill paid from alert now includes a generation marker to avoid duplicates.

Important: P/L is the difference between saved cost and current value, NOT realized P/L. It may be misleading if a user has withdrawals, distributions, or incomplete historical cost. No automatic NAV refresh offline.

Before deployment: back up v5. Install all files, open online once, close/reopen, verify offline, assets, cards, balances, receipts, and backup/restore. Test loan due-alert payment carefully.
