# Publish to GitHub Pages

This project can be published to GitHub Pages. Follow these steps:

1. Create a new GitHub repository (public) named `Clayton_Ladner_c9_analyze`.
2. From the project root, initialize git, add files, commit and push:

```powershell
git init
git add .
git commit -m "Initial commit for GitHub Pages"
git branch -M main
git remote add origin https://github.com/<your-username>/Clayton_Ladner_c9_analyze.git
git push -u origin main
```

3. Enable GitHub Pages in the repository settings (Pages) or use the `gh-pages` branch via Actions.

Notes:
- GitHub Pages will serve static files over HTTPS. After publishing, your site will be available at `https://<your-username>.github.io/Clayton_Ladner_c9_analyze/`.
- Verify that VTT files are served with the correct `Content-Type`. GitHub Pages usually serves common types correctly; if you see issues, test with the Network tab.
