# Deena Kiran M K Portfolio

Static portfolio website built with plain HTML and CSS.

## Deploy on Render

This repository includes a root `render.yaml` configured to deploy the `portfolio` folder.

1. Go to Render Dashboard.
2. Choose **New +** -> **Blueprint**.
3. Connect this GitHub repository: `DeenaKiranMK/DeenaKiranMK`.
4. Render will create a static site with:
   - Service name: `deena-kiran-portfolio`
   - Build command: `true`
   - Publish path: `portfolio`

## Manual Render Static Site Settings

If you choose **New +** -> **Static Site** instead of Blueprint, use:

- Root Directory: leave blank
- Build Command: `true`
- Publish Directory: `portfolio`

After deployment, Render will provide a public `onrender.com` URL.
