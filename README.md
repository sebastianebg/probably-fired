# Probably Fired

Static LinkedIn gimmick tool for discovering exactly why your job has been automated.

Live: https://probably-fired.vercel.app

## What It Does

- Takes any job title.
- Generates a fake AI redundancy notice.
- Tailors reasons to broad role categories such as engineering, sales, legal, finance, teaching, healthcare, design, and consulting.
- Runs entirely in the browser. No backend, no API key, no user data collection.

## Local Use

Open `index.html` directly in a browser.

Or run a local static server:

```bash
npm run dev
```

## Deployment

This can be hosted as a single static page on Vercel, Netlify, GitHub Pages, Cloudflare Pages, or any object store/CDN.

The Vercel production build serves the repo root as static output.

## Notes

The concept was inspired by the viral "find out if you can be replaced" pattern at `https://replacebyclawd.com/`, but the implementation and copy here are original.
