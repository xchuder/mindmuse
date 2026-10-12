# Mindmuse

A free mind map, sitemap and diagram board that runs entirely in the browser. No account, no server, no build step: the whole app is one static file, `index.html`.

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
npx http-server . -p 8080
```

## Deploy

Any static host works. On Vercel, import this repository and keep the defaults (Framework Preset: Other, no build command, no output directory).

## Notes

- Boards autosave in the browser's local storage.
- Fonts load from Google Fonts. Icons are inlined from [Lucide](https://lucide.dev) (ISC License).
- Export, Excel import and Save to file are being built; see the roadmap in the project thread.
