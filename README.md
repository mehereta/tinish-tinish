# Tinish Tinish: daily Amharic

A small installable web app for learning everyday Amharic.

## Publish on GitHub Pages
1. Create a new **public** repository on GitHub.
2. Upload every file in this folder (keep the `icons/` folder), then commit.
3. Settings → Pages → Source: **Deploy from a branch** → `main` / `(root)` → Save.
4. Open `https://<your-username>.github.io/<repo-name>/` after a minute or two.

## Releasing an update
1. Upload the changed files to the repository.
2. In `sw.js`, change `VERSION` (for example `'v1'` → `'v2'`) so installed phones fetch new icons and files.
