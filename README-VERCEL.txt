MASTER COMMAND — VERCEL PWA v4

DEPLOY:
1. Upload the CONTENTS of this folder to the root of your Vercel project.
2. Redeploy.
3. Open the HTTPS Vercel URL in Chrome Android.
4. Open Chrome menu and check "Install app".

IMPORTANT:
- Do not open index.html with file://.
- The PWA files must be at the site root:
  /manifest.json
  /sw.js
  /icon-192.png
  /icon-512.png
- After deploying v4, use "Bersihkan cache PWA" in the diagnostic panel if the phone still has the old service worker.
