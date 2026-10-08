# Woodlands Indoor Bowls Reserve League

Source backup of the existing privately hosted app. Cloudflare migration is in preparation; this is not yet a standalone deployment.

The app includes fixtures, results, points per triple, player position stats, editable reserves, team selection, and the WhatsApp poster.

Before deploying in a separate account, replace the Sites-specific build/auth configuration, create a separate D1 test database, apply the two schema migrations, and protect the app and API with sign-in. Saved production data is not included in these source files.
