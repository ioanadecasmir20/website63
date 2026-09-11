TALON GROUP WEBSITE – ROBUST STATIC BUILD

UPLOAD
1. Extract this ZIP on your computer or in your hosting File Manager.
2. Upload ALL CONTENTS directly into the document root for talongroup.co.uk (normally public_html).
3. Do NOT upload the outer folder itself as an extra level.
4. The root must contain index.html, .htaccess, .nojekyll, assets/, images/, about/, contact/, etc.

IMPORTANT
- This build contains the full styling INSIDE every HTML page as a fallback, as well as assets/css/style.css.
- Therefore the website will still be styled even if the hosting server temporarily fails to load the external CSS file.
- JavaScript is also embedded as a fallback and provided separately in assets/js/script.js.
- Internal public URLs do not use .html. Home is linked as / and pages are linked as /about/, /contact/, etc.
- Keep the folder names exactly as supplied.

AFTER UPLOAD
Open https://www.talongroup.co.uk/ and hard refresh the browser (Ctrl+F5 on Windows or Cmd+Shift+R on Mac).
If a CDN/cache is enabled in the hosting panel, purge its cache once after uploading.

IMAGES
Replace images inside /images/ if desired, keeping the same filenames to avoid changing code.
