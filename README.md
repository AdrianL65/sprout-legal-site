# sprout-legal-site

Privacy policy, terms and account-deletion pages for **Sprout**, served by GitHub Pages at
**https://sprout-legal.mikrodev.net**.

| Path | Store field |
|---|---|
| `/privacy/` | App Store "Privacy Policy URL", Play "Privacy policy" |
| `/terms/` | "Terms of Use" link (App Store description, in the app, the sign-up agreement). The App Store EULA itself stays **Apple's Standard EULA** (decision 2026-09-22: a custom EULA must show an address and phone) |
| `/delete-account/` | Play Console "Delete account URL" |

Home and help live in the sibling site `sprout-support-site` (https://sprout-support.mikrodev.net).

## Rules
- Every claim here must match what the app actually does. The research behind the wording is in
  `Publishing-Docs/10 - Legal & Store Policy Research.md`, and the security rules in `Publishing-Docs/13 - Security Baseline (Apps, Databases, Websites).md`. When the app starts collecting something new,
  or adds a new service (SDK, processor), update `/privacy/` **before** that release ships.
- Change the "Last updated" date on any page you change in substance.
- `assets/site.css` is copied from `sprout-support-site`. Edit it there, then copy it here.
- Preview: `python3 -m http.server 8000`, then open http://localhost:8000.
