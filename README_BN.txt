BloodMarket final layout package.

Public page:
- index.html
- Product prices are visible to visitors.
- Buy/Sell actions require Firebase Login/Sign up.
- Admin button/link is not shown on the public page.

Separate admin page:
- admin.html
- Admin can sign in separately and save public prices to Firestore at siteSettings/public.

Important:
- Keep your existing firebase-config.js in the GitHub repository.
- The sample demo prices are Facebook Buy 500, Facebook Sell 350, Email Buy 300, Email Sell 250.
- For real production security, Firestore rules/custom admin claims must restrict writes to siteSettings and orders.
