# BreakCycle

A mobile-friendly prototype for tracking paycheck advances, forecasting cash flow, and exploring gradual reductions in repeat borrowing.

## Try locally

Open `index.html` in a modern browser. For reliable testing, use a local web server:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages

1. Create a **public** GitHub repository named `breakcycle`.
2. Upload `index.html`, `README.md`, and `.nojekyll` to the repository root (or push this folder with Git).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**; select branch **main**, folder **/(root)**, then **Save**.
5. Once deployed, open `https://YOUR-USERNAME.github.io/breakcycle/`.

Note: GitHub Pages availability and settings may vary by plan. A public repository is simplest for free hosting.

## Important limitations

- Prototype only; not financial advice, a lender, or a payment processor.
- No bank connections or user accounts.
- Entries are stored in the browser's localStorage where supported; **not encrypted** and not synchronized between devices.
- Do not enter sensitive identifiers or use on shared devices.
- Exit Plan is illustrative, not a validated repayment recommendation. Confirm repayment terms, due dates, and essential expenses.
- Hosting this static site does not make it a secure production financial application.

## Development

Current version: v0.3. Next priorities: test adding advances on hosted mobile browsers; track due dates; handle multiple paychecks and essential bill dates; improve accessibility and privacy protections.
