# ie-portfolio-deploy

Portfolio for Megan Amasa's Duke Innovation & Entrepreneurship (I&E) Certificate.

## Pages
| Page | File |
|---|---|
| My Story | `index.html` |
| Coursework | `coursework.html` |
| Experiences | `experiences.html` |
| Artifacts | `artifacts.html` |

Shared styles live in `style.css`; images in `images/`.

## Access
Pages sit behind a lightweight client-side password gate (session-scoped). It keeps casual visitors out — it is not real authentication.

## Run locally
```bash
open index.html          # or: npx serve .
```

## Deploy
Static site on Vercel. Pushes to `main` deploy to production.
