# The Head Start Planner

A Vite + React project wrapping your `HeadStartPlanner` component, ready to deploy to GitHub Pages.

## One-time setup

1. Create a new repo on GitHub (public, since GitHub Pages needs public or a paid plan for private).
2. Unzip this project and push it:

   ```bash
   cd headstart-planner
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-repo>.git
   git push -u origin main
   ```

3. In the repo on GitHub: **Settings → Pages → Build and deployment → Source → GitHub Actions**.

That's it. The workflow in `.github/workflows/deploy.yml` will build and deploy automatically on every push to `main`. Check the **Actions** tab to watch it run — first deploy takes a minute or two. Your site will be live at:

```
https://<your-username>.github.io/<your-repo>/
```

## Local development

```bash
npm install
npm run dev
```

Opens at `http://localhost:5173`.

## Making changes

Edit `src/HeadStartPlanner.jsx`, then just `git push` — the site updates automatically.
