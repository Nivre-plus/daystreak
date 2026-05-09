Day Streak Offline PWA Upload Instructions

Upload/replace these files in the ROOT of your GitHub repository:
- index.html
- manifest.webmanifest
- service-worker.js
- icon-192.png
- icon-512.png
- .nojekyll

Important:
- Upload the files themselves, not only the folder.
- index.html must be at the same level as README.md.
- If GitHub asks, choose "Commit changes".

After uploading:
1. Open your GitHub Pages app link while online.
2. Wait until the top badge says "Offline ready" or reload once.
3. In Chrome, tap ⋮ → Add to Home screen / Install app.
4. Open it once from the home screen while online.
5. After that, it should open without internet.

Your streak data is saved on that phone/browser with localStorage. Clearing browser/site data can erase it.
