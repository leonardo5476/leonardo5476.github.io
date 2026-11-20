# Leonardo Cunha: Portfolio

A static one-page portfolio built for GitHub Pages. It has no build step.

## Files
- `index.html`: the page content
- `config.js`: **edit this file** to set contact links, the Upwork URL, the photo path, and the contact mode
- `assets/photo.jpg`: your portrait (add it yourself; until then the page shows an "LC" monogram)

## Publish on GitHub Pages
1. Create a repository named `<your-username>.github.io` (or use any repo name, which serves the site at `/<repo>/`).
2. Upload these files to the root of the `main` branch.
3. Go to **Settings → Pages → Source: Deploy from a branch → `main` / root**.
4. In `index.html`, replace `YOUR-USERNAME` in the `og:url` / `og:image` tags so link previews show your photo.

## Contact modes (config.js)
- `"upwork"` (default): the page shows no email, phone, or LinkedIn. Visitors are sent to your Upwork profile.
  Use this while the link appears on Upwork, because Upwork forbids sharing direct contact details with clients before a contract starts.
- `"public"`: shows email, phone, and LinkedIn. Anything you put in `config.js` is publicly readable.
