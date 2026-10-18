STUDENT HUB — QUICK START

Files:
- index.html: the app
- manifest.json: installable PWA settings
- sw.js: offline caching
- icon.svg: app icon

FEATURES
- Dashboard overview
- Timetable with days, times and locations
- Assignment tracker with due dates, priorities and completion checkboxes
- Notes with editing and deletion
- Focus timer with 25-minute focus and short/long breaks
- Weighted GPA calculator
- Profile name
- Local storage so information stays on this browser/device
- Responsive mobile layout and PWA/offline support

IMPORTANT
Your information is stored in the browser on the device you use. It is not synced to other devices. Clearing browser site data may erase it. For full install/offline support, host the files on HTTPS; opening index.html directly still allows the main app to work, but service-worker installation requires a web server.

FREE HOSTING OPTION A — NETLIFY DROP
1. Extract the ZIP on your phone or computer.
2. Open https://app.netlify.com/drop in Chrome.
3. Sign in or create a free account if asked.
4. Upload/drag the extracted student_hub folder contents (index.html, manifest.json, sw.js, icon.svg) into the drop area.
5. Open the HTTPS website Netlify gives you.
6. In Chrome on Android, open the site menu (⋮) and choose “Install app” or “Add to Home screen”.

FREE HOSTING OPTION B — GITHUB PAGES
1. Create a free GitHub account and a new public repository.
2. Upload index.html, manifest.json, sw.js and icon.svg to the repository root.
3. Open Settings → Pages, select deployment from the main branch/root folder, and save.
4. Open the generated HTTPS Pages URL on your Android phone.
5. Use Chrome’s menu to install/add to home screen.

If you update the app files, upload the updated files to the same hosting location. Data stored locally in your browser is separate from the hosted app files.
