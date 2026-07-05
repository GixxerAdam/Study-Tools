CySA+ PWA v2 update

Upload these four files to the ROOT of your GitHub repository, replacing the existing files:
- index.html
- sw.js
- manifest.webmanifest
- icon.svg

Commit directly to main. GitHub Pages will update in about 1–5 minutes.

On iPhone: open the site in Safari and refresh once. If the old app is installed on your Home Screen, close it, open the website in Safari once, then reopen the Home Screen app. The updated service worker will replace the old cached version.

Important: v2 uses a fresh local progress store because the older version had malformed parsing in later questions.
