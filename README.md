# Basic Website Starter

A beginner-friendly static website using HTML, CSS, and JavaScript. It can be published for free with GitHub Pages.

## Folder structure

- `index.html` — the main webpage
- `css/style.css` — layout, colors, fonts, and responsive design
- `js/script.js` — small interactive features
- `assets/favicon.svg` — browser tab icon
- `README.md` — project notes
- `.gitignore` — files Git should ignore

## Customize it

1. Open `index.html` in your code editor.
2. Change `My Website`, the page text, and the example email address.
3. Edit `css/style.css` to change the colors and appearance.
4. Add your images inside `assets/` and reference them from HTML, for example: `<img src="assets/my-photo.jpg" alt="Description of the photo">`.
5. Open `index.html` in a browser to preview the site.

## Publish using GitHub Pages

1. Sign in to GitHub and create a **new repository**.
2. Upload the contents of this folder to the repository's root. Make sure `index.html` is at the top level, not inside another nested folder.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose branch `main` and folder `/(root)`, then save.
6. Wait a few minutes. The Pages section will show your public website address.

## Publish with Git commands

Run these commands in a terminal opened inside this folder, replacing the example repository URL with your own:

```bash
git init
git add .
git commit -m "Add basic website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```

Then enable GitHub Pages in **Settings → Pages** as described above.

## Important

This is a static website. It does not include a backend, database, login system, or working contact form. The email button opens the visitor's email app.
