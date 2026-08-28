# Publish This Portfolio to GitHub

## Recommended repository name
`mechanical-engineering-portfolio`

## Option A — GitHub website upload
1. Create a new public repository named `mechanical-engineering-portfolio`.
2. Do not initialize it with a README if you plan to upload this full package.
3. Upload the contents of this folder to the repository root.
4. Commit with the message: `Launch mechanical engineering portfolio`.
5. Pin the repository on your GitHub profile.

## Option B — Git command line
From inside this folder:

```bash
git init
git add .
git commit -m "Launch mechanical engineering portfolio"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/mechanical-engineering-portfolio.git
git push -u origin main
```

## Turn on GitHub Pages
1. Open the repository on GitHub.
2. Go to Settings → Pages.
3. Under Build and deployment, choose **Deploy from a branch**.
4. Select branch `main` and folder `/docs`.
5. Save.

The included `docs/index.html` is the portfolio landing page.

## Profile README option
If you want this portfolio summary directly on your GitHub profile, create a repository with the exact same name as your GitHub username and copy/adapt the main `README.md` into it.
