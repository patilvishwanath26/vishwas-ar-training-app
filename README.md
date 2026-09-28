# VISHWAS AR

Immersive AR safety training & digital compliance platform — prototype.

## Current state

This repository currently contains a single self-contained interactive
prototype:

```
web/index.html
```

It simulates the Worker app (onboarding, AR training modules, assessments,
certificates, QR verification, SOS/emergency flow, profile & settings) and
the Admin/Employer web dashboard in one static HTML/CSS/JS file. All data is
stored client-side in `localStorage` — there is no backend, database, or API
key in this build yet.

### Run locally

Just open `web/index.html` in a browser, or serve the folder:

```bash
npx serve web
```

## Roadmap (not yet implemented)

- Native Android app (Flutter) with ARCore
- Firebase Authentication / Firestore / Storage backend
- React-based production admin dashboard
- Real push notifications, real QR camera scanning

No credentials or environment files should ever be committed to this repo —
see `.gitignore`.
