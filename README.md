# Zee by the Sea

Static website for Zee by the Sea.

## Important deployment note
The ZIP supplied with this version has `index.html`, `style.css`, `script.js`, `netlify.toml` and the `assets` folder at the ZIP root. Keep the `assets` folder beside `index.html` so all images load correctly.

## GitHub + Netlify
1. Create/open the GitHub repository.
2. Upload **all files and the entire `assets` folder** to the repository root.
3. In Netlify choose **Add new site → Import an existing project**.
4. Select the GitHub repository.
5. Build command: leave blank.
6. Publish directory: `.`
7. Deploy.

All image references use relative `./assets/...` paths, so they work on both GitHub Pages and Netlify project URLs.
