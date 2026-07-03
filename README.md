# Restroom Report — Legal & Support Site

This repository hosts the public legal and support pages for the **Restroom Report** iOS app, served via **GitHub Pages** at **https://truesolutionsllc.github.io/RestroomReport-Site/**.

## Pages

| Path | File | Purpose |
|------|------|---------|
| `/` | `index.html` | Landing page |
| `/privacy` | `privacy.html` | Privacy Policy |
| `/terms` | `terms.html` | Terms of Service |
| `/support` | `support.html` | Support / help |
| (any unmatched path) | `404.html` | Page not found |

> GitHub Pages automatically serves `privacy.html` at `/privacy`, `terms.html` at `/terms`, and `support.html` at `/support`, which is why the app's App Store URLs use the extension-less paths.

## Custom domain

The `CNAME` file configures the GitHub Pages custom domain (`restroomreport.app`). Do not remove it.

## How to update

1. Edit the relevant HTML file directly (`privacy.html`, `terms.html`, `support.html`, `index.html`).
2. Shared styling lives in `styles.css`.
3. Update the "Last updated" date in the page footer(s) when content changes.
4. Commit and push to the default branch; GitHub Pages redeploys automatically.

All pages use **relative links** and a single shared stylesheet, so the site works correctly at the domain root.

## Source of truth

The legal and support text is generated from draft documents that live in the **Restroom Report app repository** (`CleanStop`):

- `PRIVACY_POLICY_DRAFT.md`
- `TERMS_OF_SERVICE_DRAFT.md`
- `SUPPORT.md`

When those drafts change, re-apply the changes here. These are drafts intended for planning; have legal counsel review the privacy policy and terms before publishing.
