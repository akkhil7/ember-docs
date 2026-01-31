# Ember Legal Documents

This repository contains the Privacy Policy and Terms of Service for the Ember app.

## Repository Structure

```
ember-docs/
└── docs/
    ├── privacy-policy.html
    ├── terms-of-service.html
    ├── support.html
    └── README.md
```

## GitHub Pages Setup

This repository is configured to host the legal documents on GitHub Pages.

### URLs

Once deployed, your documents will be available at:
- Privacy Policy: `https://yourusername.github.io/ember-docs/docs/privacy-policy.html`
- Terms of Service: `https://yourusername.github.io/ember-docs/docs/terms-of-service.html`
- Support: `https://yourusername.github.io/ember-docs/docs/support.html`

### Deployment

1. Push to GitHub
2. Go to Settings → Pages
3. Select source: "Deploy from a branch"
4. Select branch: `main` and folder: `/docs`
5. Save

## Updating Documents

1. Edit the HTML files in `docs/`
2. Commit and push:
   ```bash
   git add docs/
   git commit -m "Update privacy policy"
   git push
   ```

## Notes

- This is a separate repository from the main app code
- Only the `docs/` folder is tracked in this repository
- The root app repository ignores this entire `ember-docs/` directory

