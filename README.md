# Broken Static Website — GitHub Pages test

This small static website intentionally includes broken links and common SEO issues for crawler testing.

Included issues:
- Several internal links point to missing pages (404s)
- One invalid external destination (`example.invalid`)
- Missing image files
- Missing meta descriptions and canonical tags
- Duplicate page titles
- Link to a missing PDF

## Publish on GitHub Pages
1. Create a repository, e.g. `broken-static-site`.
2. Extract this ZIP and upload all files/folders to the repository root.
3. Go to **Settings → Pages**.
4. Choose **Deploy from a branch**; select branch `main` and folder `/(root)`.
5. Save and wait for the published URL.

Usually the URL is `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

Intentionally broken for testing only; not a production website.
