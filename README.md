# bookbuddy-site

Marketing one-pager and App Store support page for [BookM@rk](https://github.com/elecumbelly/BookMark), the iOS book-library app (App Store name **BookM@rk**; app repo renamed to BookMark 2026-06-11, old links redirect. Internal identifiers — bundle ID, scheme, Xcode project, this site's repo/domain — keep the Bookbuddy name).

- **Production:** https://bookbuddy.collapsingwavefunctions.com (Vercel)
- Static HTML/CSS, no build step — edit `index.html`, commit, then deploy manually with `vercel deploy --prod` (GitHub auto-deploy is not connected to this repo).
- Light/dark mode: follows the visitor's system preference; the manual toggle persists via `localStorage`.
- This page is the app's **Support URL** in App Store Connect; keep the contact link working.
- Screenshots in `assets/` are simulator captures from the app repo (regenerate with the `-seedSampleData -hasSeenWelcome YES` launch arguments).
