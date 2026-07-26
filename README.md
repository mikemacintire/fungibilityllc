# fungibilityllc.com

Company website for Fungibility LLC — a static, three-page site with no build step.

| File | Purpose |
| --- | --- |
| `index.html` | Company page: products, approach, company record, contact |
| `privacy.html` | Privacy policy |
| `terms.html` | Terms of service |

Each file is self-contained: styles are inlined, and the only external request is
to Google Fonts (Newsreader and IBM Plex Mono). There are no dependencies to
install and nothing to compile.

## Local preview

Open `index.html` in a browser, or serve the directory:

```bash
npx serve .
```

## Deployment

Deployed on Vercel as a static site, built from the `main` branch. Pushing to
`main` triggers a production deploy.
