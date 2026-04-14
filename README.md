# FlowBridge CMS Starter

This starter keeps your main pages static while turning **Resources** and **Insights** into publishable sections.

## What is included
- `index.html`, `about.html`, `services.html` as static pages
- `resources/index.html` as a listing page for posts and downloads
- `insights/index.html` as a listing page for landing pages and insight entries
- `_resources/` for resource entries
- `_insights/` for insight entries
- `_layouts/` for the reusable Jekyll page layouts
- `.pages.yml` for Pages CMS
- `_config.yml` for GitHub Pages / Jekyll collections
- `assets/images/` for uploaded images
- `downloads/` for ebooks and files

## Recommended free stack
- Host on GitHub Pages
- Use Pages CMS with the `.pages.yml` file in the repository root

## Publishing flow
1. Push this folder to a GitHub repository.
2. Enable GitHub Pages for the repository.
3. Open Pages CMS and connect the repository.
4. Add new resource posts, downloads, or insight pages from the CMS.
5. GitHub Pages rebuilds the site and publishes the new content.

## Notes
- Resource entries are saved in `_resources/`
- Insight entries are saved in `_insights/`
- Both listing pages automatically loop through entries with Jekyll/Liquid
- Replace placeholder content before going live
