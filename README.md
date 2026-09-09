# Exam Prep Notes

Study notes site built with Jekyll + the "Just the Docs" theme, hosted free
on GitHub Pages. Math renders via MathJax (including chemistry equations
via the mhchem extension) directly in the browser — no LaTeX conversion
needed, ever.

## Structure

```
math/          -> one .md file per topic
physics/       -> one .md file per topic
chemistry/     -> one .md file per topic
biology/       -> one .md file per topic
_includes/     -> MathJax script (do not edit)
_config.yml    -> site + theme config (do not need to touch again)
PROMPT_TEMPLATE.md -> reusable prompt for generating new pages
```

## Publishing this to GitHub Pages

1. Create a new **public** repository on GitHub (any name, e.g. `exam-prep`).
2. From this folder, run:
   ```
   git init
   git add .
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
3. On GitHub: go to the repo's **Settings → Pages**, and under "Build and
   deployment" set Source to "Deploy from a branch", Branch to `main`,
   folder to `/ (root)`. Save.
4. Wait 1-2 minutes. Your site will be live at:
   `https://<your-username>.github.io/<repo-name>/`

No local Jekyll install or build step is required — GitHub builds it for
you automatically on every push.

## Adding a new topic page

1. Open `PROMPT_TEMPLATE.md`, fill in the topic/subject, and send it to
   an AI assistant.
2. Paste the output, unedited, into a new file inside the matching subject
   folder (e.g. `physics/newtons-laws.md`).
3. Commit and push:
   ```
   git add .
   git commit -m "Add [topic]"
   git push
   ```
4. The page appears in the sidebar automatically (sorted by `nav_order`).
