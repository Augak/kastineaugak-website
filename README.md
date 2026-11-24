# Kastine Augak — Official Website

The source repository for the official Kastine Augak website.

- **Live website:** https://kastineaugak.netlify.app/
- **GitHub repository:** https://github.com/Augak/kastineaugak-website
- **Owner:** Kastine Augak

## About

A personal and professional website presenting Kastine Augak's work in software engineering, artificial intelligence, technology, innovation, educational technology and digital media.

## Existing website migration

The initial site files are imported from the live Netlify website rather than from a different portfolio repository. To create the first source snapshot:

1. Open the **Actions** tab.
2. Select **Import live Netlify site**.
3. Select **Run workflow** on the `main` branch.
4. Wait for the workflow to finish, then review the files and commit.

The workflow mirrors the publicly accessible website pages and their same-domain assets into this repository. It does not change or redeploy the live Netlify website.

If GitHub blocks the workflow from committing, open **Settings → Actions → General → Workflow permissions**, select **Read and write permissions**, and save.

## Development principles

- Preserve existing pages, content, URLs and working features.
- Keep the site mobile-first, accessible and fast on low-end Android devices.
- Optimize images, SVGs, CSS and JavaScript without removing useful content.
- Maintain canonical URLs, sitemap, robots.txt and structured data carefully.
- Test changes before publishing them to the live site.

## Deployment

The live website remains hosted on Netlify. Connecting this repository to the existing Netlify site is a separate step and should be done only after the imported source has been reviewed.

## Author

**Kastine Augak**  
Technology · Innovation · Research · Digital Media
