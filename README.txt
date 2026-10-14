Grit & Glitch – Shipping Slips (installable web app)

WHAT'S IN THIS FOLDER
  index.html            the app
  manifest.webmanifest  app name, icon and colours for installing
  sw.js                 lets the app open without internet
  icons/                app icons

HOW TO PUT IT ONLINE
  Upload ALL of these files, keeping the same folder layout, to any website host
  that uses https (Netlify, GitHub Pages, Cloudflare Pages, Vercel, or your own hosting).
  Easiest: drag this whole folder onto https://app.netlify.com/drop
  It must be https (or localhost) – apps cannot be installed from a plain file.

HOW TO INSTALL IT
  Android / Chrome / Edge (phone or computer): open the site, then tap "Install"
  when asked, or use Settings (gear) > "Install app", or the browser menu > "Install app".
  iPhone / iPad: open the site in Safari > Share > "Add to Home Screen".

UPDATING
  Replace index.html on your host. The app checks for the new version whenever it is
  online and shows "App updated – Reload".
  If you change icons or the manifest, also change 'gg-shell-v1' in sw.js to 'gg-shell-v2'.

NOTES
  Passcode: 9874. Slips and settings are saved on each device separately.
  An app installed on iPhone keeps its own data, separate from Safari.
