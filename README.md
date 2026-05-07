# Anonymous Project Page

This folder contains a static anonymous project page for `MetroSurv-Bench`.

## Files

- `index.html`: the main page
- `styles.css`: page styling
- `assets/`: local images used by the page

## Local Preview

Open `index.html` directly in a browser, or run a simple static server:

```bash
cd anonymous_project_page
python -m http.server 8000
```

Then visit `http://127.0.0.1:8000`.

## Deploy to Gitee Pages

Recommended anonymous workflow:

1. Create a new Gitee repository that does not contain your name, lab name, or organization name.
2. Upload the contents of this folder to the repository root.
3. In the Gitee repository settings, enable Gitee Pages.
4. Choose the default branch and publish from the repository root.
5. Use the generated public URL for the anonymous submission page.

## Anonymous Release Notes

- Do not add author names, affiliations, email addresses, or personal repository links before review ends.
- The teaser figure `construction-modified2.png` has already been added to `assets/` and is shown near the top of `index.html`.
