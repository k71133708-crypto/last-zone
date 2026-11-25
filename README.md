# Last Zone - Web App Setup

## Files in this folder
- index.html : the game
- manifest.json : app info (name, icon, landscape, fullscreen)
- sw.js : offline support and install support
- icon-192.png, icon-512.png : app icons
- privacy.html : privacy policy (fill in your email and date first)

## Steps (GitHub Pages, free)
1. Create a free account at github.com (you do this yourself).
2. Click "New repository". Name it: last-zone. Set it to Public. Click Create.
3. Click "uploading an existing file". Drag ALL files from this folder (not the folder itself) into the page. Click "Commit changes".
4. Go to Settings > Pages. Under "Build and deployment", choose Source: Deploy from a branch, Branch: main, folder: / (root). Click Save.
5. After 1-2 minutes your game will be live at:
   https://YOUR-USERNAME.github.io/last-zone/
6. Open that link on an Android phone in Chrome. Tap the menu (three dots) > "Install app" or "Add to Home screen". The game opens fullscreen from its own icon.

## Updating the game later
Upload the new index.html to the same repository (replace the old one). Change the CACHE name in sw.js (for example last-zone-v2) so phones fetch the new version.

## Before publishing
- Fill in your email and date in privacy.html.
- Keep the privacy link handy if you ever apply to a store.
