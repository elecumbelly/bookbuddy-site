# bookbuddy-site

Marketing one-pager and App Store support page for [BookM@rk](https://github.com/elecumbelly/Bookbuddy), the iOS book-library app (App Store name **BookM@rk**; internal project name Bookbuddy — repo, domain, and paths keep the old name).

- **Production:** https://bookbuddy.collapsingwavefunctions.com (Vercel)
- Static HTML/CSS, no build step — edit `index.html`, push to `main`, Vercel deploys.
- This page is the app's **Support URL** in App Store Connect; keep the contact link working.
- Screenshots in `assets/` are simulator captures from the app repo (regenerate with the `-seedSampleData -hasSeenWelcome YES` launch arguments).
