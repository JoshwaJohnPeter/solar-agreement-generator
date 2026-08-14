# Solar Agreement Generator

This is the single-file solar agreement generator packaged as a small HTTPS-ready web app.

## Important for mobile Share Word

The browser's native file sharing API requires a secure context:
- HTTPS website, or
- localhost during development.

After deployment, open the HTTPS address on the phone in Chrome/Safari.
Then Share Word can open the native share sheet with the generated DOCX attached.

## Easy deployment

### Netlify
1. Create a free Netlify account.
2. Choose Add new site -> Deploy manually.
3. Upload this folder (or unzip the ZIP).
4. Netlify gives you an HTTPS URL.
5. Open that URL on your phone.

### GitHub Pages
1. Create a GitHub repository.
2. Upload `index.html`, `manifest.webmanifest`, and `service-worker.js`.
3. Enable GitHub Pages for the repository.
4. Open the HTTPS Pages URL on your phone.

Do not open the HTML using `file://` if you want direct mobile file sharing.
