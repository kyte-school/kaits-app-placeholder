# kaits-app-placeholder

A holding page at https://app.kaits.maic.club, the address the KAITS parent app will use (activation links `/i/<code>`, payment pages `/pay/<code>`). WhatsApp templates point there, so the address has to load while the app isn't hosted yet. `404.html` is the same page, so any path (for example an activation link) shows it.

When the real app is deployed, point the `app.kaits` DNS record at the app's server and set `KAITS_WEB_URL=https://app.kaits.maic.club`. This repo can then be archived.
