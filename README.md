# CarCare.help website

Static marketing site for CarCare.help (Car Registration Help Inc.). Plain HTML, CSS and a little JavaScript: no build step.

## Files
- `index.html` — homepage (deduction calculator, features, voice, shop finder, safety, pricing, FAQ)
- `about.html` — About page
- `privacy.html` — Privacy Policy (draft for counsel review)
- `terms.html` — Terms of Service (draft for counsel review)
- `assets/carcare-logo.jpg` — logo

## Run locally
Open `index.html` in a browser, or serve the folder:

    python3 -m http.server 8000

## Deploy
- Vercel: `npx vercel deploy --prod` from this folder (live at https://carcare-demo.vercel.app)
- GitHub Pages: push to `main` of meeng1223/carcare-demo (live at https://meeng1223.github.io/carcare-demo/)

## Before launch
- The early-access email form isn't connected to a mailing list yet (see the `signup` handler at the bottom of `index.html`).
- Privacy Policy and Terms must be reviewed by outside counsel (plan items LEG-01, LEG-02). See `legal-compliance-check.md` (kept out of the public repo).
