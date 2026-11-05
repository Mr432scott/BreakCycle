# BreakCycle v1.4 — Unified Loans

- Removed the separate Exit Plan navigation tab.
- The **Loans** tab now contains installment loans, payday loans/advances, actual repayment recording, and future borrowing-reduction scenarios.
- Dashboard progress cards now include payday loans. **Recorded payoff progress** is calculated from the balance when first entered (or migrated) and repayments manually recorded within BreakCycle. It does not confirm a lender's balance.
- Repeating payday advances also show a **separate hypothetical future borrowing reduction** progress bar. This is not the same as paying down debt.
- Payday loan obligations continue to appear with bills on the calendar. Recording a repayment updates the tracked amount due; it does not send money or modify lender terms.
- Existing `bc_advances`, `bc_reductions`, and `bc_loans` localStorage data are retained.

Upload `index.html` to your GitHub Pages repository. Use fictional data while testing; financial information is stored in browser localStorage without encryption.
