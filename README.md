# CyberVendorGuide

A static HTML cybersecurity publication intended for GitHub Pages.

## Publish

1. Create the public GitHub repository `Drominaman/cybervendorguide`, initialized with a README.
2. Upload or commit the files in this folder to the root of the `main` branch (including `posts/`, `assets/`, and `.nojekyll`).
3. In repository **Settings → Pages**, under **Build and deployment**, choose **Deploy from a branch**, select **main** and **/(root)**, then save.
4. The website address will be `https://drominaman.github.io/cybervendorguide/` after GitHub Pages deploys the site.

No site generator, build step, database, JavaScript framework, analytics, or external dependencies are required.

## New articles

Create a new HTML file in `posts/` using `posts/how-to-evaluate-a-cybersecurity-vendor.html` as a template. Add it to the article section of `index.html`, then update `sitemap.xml` and `feed.xml`. Use relative links to assets as shown in the template.

## Privacy

This is a public GitHub Pages website. The repository owner, commit history, and public files can be inspected on GitHub. Review your GitHub profile and commit email settings before publishing if identity separation matters to you.


## October 2026 SBOM tools guide

The featured article is `posts/best-sbom-tools-2026.html`. When updating it, keep `index.html`, `feed.xml` and `sitemap.xml` in sync.
