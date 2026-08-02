# Scythe legal

Public legal pages for apps published under **Scythe** (privacy policies, etc.).

**Hub:** https://juancamilo87.github.io/scythe-legal/

## Apps

| App | Privacy policy URL |
|-----|--------------------|
| Sip | https://juancamilo87.github.io/scythe-legal/sip/privacy.html |
| Cloudless | https://juancamilo87.github.io/scythe-legal/cloudless/privacy.html |

Paste the app URL into Play Console → App content → Privacy policy.

When migrating from [cloudless-legal](https://github.com/juancamilo87/cloudless-legal), update the Play listing to the Cloudless URL above, then archive/delete the old repo.

## Adding another app

1. Create `your-app/privacy.html` (copy `sip/privacy.html` and edit).
2. Link it from `index.html`.
3. Push to `main` — GitHub Pages updates in place; no new URL scheme required per version.

Same pattern as [cloudless-legal](https://github.com/juancamilo87/cloudless-legal).
