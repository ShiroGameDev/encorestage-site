# EncoreStage public site

A small, static informational and legal website for the **EncoreStage** K-pop media brand. It describes the brand and its private internal publishing integration, and hosts the Privacy Policy and Terms of Service needed for platform configuration.

The public site is plain HTML and CSS. It does not use a Node runtime, a database, analytics, advertising pixels, tracking scripts, or site-set cookies. It is not a public software product and does not offer access to the internal publishing workflow.

## GitHub Pages

This repository is intended to publish directly from the `main` branch and repository root:

1. Open the repository's **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/ (root)`, then save.

Expected project-site URLs for this repository:

- Website: <https://shirogamedev.github.io/encorestage-site/>
- Privacy Policy: <https://shirogamedev.github.io/encorestage-site/privacy.html>
- Terms of Service: <https://shirogamedev.github.io/encorestage-site/terms.html>

GitHub Pages may take a few minutes to publish after it is enabled. Use the exact URLs shown by GitHub Pages when entering the website and policy links in a platform developer console.

All internal page and stylesheet links are relative, so they work below the `/encorestage-site/` project-site prefix.

## TikTok URL verification files

Do not create a verification file until TikTok supplies the exact filename, contents, and required URL/path. When provided, add the file to this repository at the path that makes its public Pages URL match TikTok's requested URL, preserving the filename, capitalization, and contents exactly. For a root-level verification URL beneath the project prefix, add the supplied file at this repository's root. If TikTok specifies another path, reproduce that path within the repository. Commit and push the file to `main`, then check the exact public URL before asking TikTok to verify it.

Do not put verification contents, tokens, or credentials in this README.

## Updating the site

Edit `index.html`, `privacy.html`, `terms.html`, or `styles.css`, then commit and push to `main`. GitHub Pages will publish the changes. Keep the legal pages aligned with the actual private publishing workflow and do not add personal contact details, account credentials, analytics, or tracking.

The public contact address supplied for EncoreStage is `encorestagekpop@gmail.com`.
