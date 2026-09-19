# Low Ember Coffee Roasters

A one-page site for a small-batch coffee roastery and bar. Built with plain HTML, CSS, and JavaScript — no build step, no dependencies.

## Project structure

```
low-ember-coffee/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── main.js
└── README.md
```

## Run it locally in VS Code

1. Open the `low-ember-coffee` folder in VS Code.
2. Install the **Live Server** extension (optional but recommended), then right-click `index.html` → **Open with Live Server**.
   - Or just double-click `index.html` to open it in a browser directly — no server required.

## Push to GitHub

From inside the `low-ember-coffee` folder:

```bash
git init
git add .
git commit -m "Initial commit: Low Ember Coffee site"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
git push -u origin main
```

Replace `YOUR-USERNAME/YOUR-REPO-NAME` with a repo you've created on GitHub (GitHub → New repository, don't initialize it with a README so it stays empty for this push).

## Customize

- **Shop name / copy**: edit the text directly in `index.html`.
- **Colors**: all defined as CSS variables at the top of `css/style.css` under `:root`.
- **Menu items & prices**: in the `#menu` section of `index.html`.
- **Fonts**: Newsreader (serif) and Archivo (sans), loaded from Google Fonts in the `<head>`.

## Deploy for free

Once pushed to GitHub, you can host it instantly with **GitHub Pages**:
1. Go to the repo on GitHub → **Settings** → **Pages**.
2. Under "Build and deployment", set Source to `main` branch, root folder.
3. Save — your site will be live at `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/` within a minute or two.
