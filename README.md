# Contact QR page

Static landing page with two actions: download a contact PDF, or open a Google Form.
Hosts free on GitHub Pages.

## Before deploy — 3 edits in `index.html`

1. **Name / role** — replace `[Your Name]` and `[Title · Organization]`.
2. **PDF** — drop your PDF in this folder. If it's not named `contact.pdf`,
   update `href="contact.pdf"` to match.
3. Form link is already wired in. Done.

## Deploy to GitHub Pages

1. Create a **public** repo, push these files (`index.html`, your `.pdf`, `README.md`).
2. Repo → **Settings → Pages** → Source: *Deploy from a branch* →
   Branch: `main`, folder: `/ (root)` → Save.
3. Live in ~1 min at `https://<username>.github.io/<repo>/`.

## QR code

Point any free QR generator at that URL. Print / share.

## Note

Repo is public → the PDF is publicly downloadable. Fine for a contact card;
don't put anything private in it.
