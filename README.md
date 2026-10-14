# CrimiReview Landing Page

A clean, minimal landing page for the CrimiReview app - a criminology board exam reviewer.

## Features Showcased

- Adaptive Learning
- Daily Challenges
- Flashcards
- Progress Tracking
- Leaderboard
- Offline Mode

## Tech Stack

- Pure HTML, CSS, JavaScript
- No frameworks or dependencies
- Mobile responsive
- GitHub Pages ready

## Deployment

The live site is https://www.crimireview.app, deployed by Vercel on every push to `main` (a GitHub Pages copy also builds at https://kilewin021105.github.io/crimireview-landing/).

`vercel.json`:
- `/download` redirects to the latest app release's `app-release.apk`, so the page links to the site's own domain. To ship a new app version, publish a new release in the app repo; the site needs no change.
- Security headers on every page: the site can't be embedded in other sites (clickjacking), plus `nosniff` and a referrer policy.

## Related

- [CrimiReview App Repository](https://github.com/kilewin021105/crimireview)
