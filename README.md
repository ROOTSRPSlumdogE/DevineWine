# Devine Wine — website files

This is the complete static website: editable HTML, CSS, JavaScript, photos, menu data and PDFs. No build step, npm dependencies, database or ChatGPT hosting is required.

## Publish with GitHub Pages

1. Create a public GitHub repository, for example `devine-wine`.
2. Extract this ZIP. Upload the CONTENTS of this folder into the repository, keeping the assets and menus folders intact. index.html must be at the repository root, not inside another folder. Include .nojekyll.
3. Commit the files to main.
4. In repository Settings > Pages, select Deploy from a branch, then main and /(root), and Save.
5. Wait for deployment. Pages will display your shareable address, usually https://YOUR-USERNAME.github.io/devine-wine/.

Official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

Upload the extracted files, not the ZIP. The source files in a public repository can be viewed by others.

## Edit the website

- index.html: main page content and structure
- style.css: appearance, responsive layouts, animations
- app.js: menus, popups, navigation, events, motion controls
- menus.json: on-page menu items, descriptions and prices
- content.json: story and other detail text
- assets/: images and logo
- menus/: downloadable menu PDFs

All local asset paths are relative, so the site supports GitHub project URLs and a custom domain. Fonts load from Google Fonts. Newsletter, application and some information links still go to the original Devine website; calls and email use the visitor's phone/email apps.

## Local preview

Serve this folder through a local HTTP server (for example VS Code Live Server). Opening index.html directly from disk can block JSON loading in menus and story popups.

This export includes the latest compact mobile award layout. It does not create a GitHub repository or change the existing hosted site's access settings.
"# DevineWine" 
