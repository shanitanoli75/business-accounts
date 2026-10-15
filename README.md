# Business & Personal Accounts Web App

A simple responsive accounting web app for:
- Mamu money received and forwarded
- Barcode rolls sold to Mamu
- Goods and payments for Noor
- Catalogic purchases, sales, gross profit and supplier balances
- Personal income, expenses, loans, repayments and pending receivables
- Dashboard, edit/delete, CSV export, JSON backup/restore

## Run locally
Open `index.html` in a modern browser.

## Publish on GitHub Pages
1. Sign in to GitHub and create a new repository (for example `business-accounts`).
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under Build and deployment, select **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then Save.
6. Wait a minute or two. GitHub will show your public website URL in the Pages section.

## Important data limitation
This starter version stores records in browser `localStorage`. It can be opened through the public URL on many devices, but each browser/device has its own separate records. Use **Backup / Settings → Download Full Backup** and import the JSON on another device to transfer records.

For automatic syncing across devices and secure login, connect a cloud database such as Firebase or Supabase. Do not put private financial records in a public GitHub repository; only the app code should be public.
