# FlowBridge hybrid starter

This version uses a hybrid workflow:

- **Resources** are created from **Pages CMS** and stored in `_resources`
- **Insights** are created manually in **GitHub** as HTML files in `_insights`

## Why this setup

This keeps blog-style content easy to manage in Pages CMS, while giving you full control over custom HTML/CSS landing pages.

## Add a Resource post

1. Open Pages CMS
2. Choose **Resources**
3. Add a new entry
4. Fill in **section** and **category**
5. Publish

## Add an Insight landing page

1. Open your GitHub repository
2. Go to the `_insights` folder
3. Create a new file ending in `.html`
4. Copy the code from `templates/insight-template.html`
5. Change the front matter values and page content
6. Commit

## Netlify notes

This setup is safe to move to Netlify later because Netlify can deploy directly from a Git repository, and your content still lives in GitHub. Pages CMS also uses `.pages.yml` at the repository root as its configuration file.
