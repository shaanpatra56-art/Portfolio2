# Shaan — Portfolio

A minimal dark portfolio site: a single `index.html` with no build step or dependencies (only the Outfit font from Google Fonts).

## Publish with GitHub Pages
1. Create a new repository on GitHub (for a root URL, name it `<your-username>.github.io`).
2. Upload these files, or push them:
   ```bash
   git init
   git add .
   git commit -m "Add portfolio"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo>.git
   git push -u origin main
   ```
3. In the repo, go to **Settings → Pages**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, then save.
4. Your site goes live at `https://<your-username>.github.io/<repo>/` within a minute or two.

## Customize
Edit `index.html`:
- Replace the email `hello@shaan.design` and the `#` social links.
- Replace the six `.tile` placeholders with your own project images (e.g. put files in `/images` and use them as `background-image`).
- Update the contact form: it currently opens the visitor's email app. For a real form backend, point it at a service such as Formspree.
