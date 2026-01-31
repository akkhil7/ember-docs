# Ember Legal Documents

This directory contains the Privacy Policy and Terms of Service for the Ember app.

## Files

- `privacy-policy.html` - Privacy Policy page
- `terms-of-service.html` - Terms of Service page
- `support.html` - Support page

## Hosting on GitHub Pages

### Option 1: GitHub Pages (Recommended)

1. **Create a new repository** (or use existing):
   ```bash
   git init
   git add .
   git commit -m "Add legal documents"
   git remote add origin https://github.com/yourusername/ember-legal.git
   git push -u origin main
   ```

2. **Enable GitHub Pages**:
   - Go to repository Settings → Pages
   - Select source: "Deploy from a branch"
   - Select branch: `main` and folder: `/docs`
   - Click Save

3. **Your URLs will be**:
   - Privacy Policy: `https://yourusername.github.io/ember-legal/privacy-policy.html`
   - Terms of Service: `https://yourusername.github.io/ember-legal/terms-of-service.html`
   - Support: `https://yourusername.github.io/ember-legal/support.html`

### Option 2: Custom Domain

If you have a custom domain (e.g., `ember.app`):

1. Add a `CNAME` file in the `docs` folder:
   ```
   legal.ember.app
   ```

2. Configure DNS:
   - Add CNAME record: `legal` → `yourusername.github.io`

3. Update GitHub Pages settings to use custom domain

## Updating the Documents

1. Edit the HTML files
2. Update the "Last Updated" date (automatically set by JavaScript)
3. Commit and push:
   ```bash
   git add docs/
   git commit -m "Update privacy policy"
   git push
   ```

## Adding to App Store Connect

Use the GitHub Pages URLs:
- **Privacy Policy URL**: `https://yourusername.github.io/ember-legal/privacy-policy.html`
- **Terms of Service URL**: `https://yourusername.github.io/ember-legal/terms-of-service.html`
- **Support URL**: `https://yourusername.github.io/ember-legal/support.html`

## Customization

Before publishing, update:
- Contact information (currently references app support feature - update if you have a website or support email)
- Jurisdiction in Terms of Service (Section 15)
- Arbitration organization (Section 16)
- Company name if different from "Ember"

## Notes

- The pages are mobile-responsive
- They use the Ember brand colors (golden yellow/orange theme)
- Last updated date is automatically set via JavaScript
- Both pages are ready to use as-is

