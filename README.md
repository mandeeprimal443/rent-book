# Rent Book – put it on your iPhone with GitHub Pages

1. Create a free GitHub account, then a new **public** repository named `rent-book`.
2. Upload ALL files and the `icons` folder from this package to the repository root
   (Add file → Upload files; keep the folder structure: index.html, manifest.webmanifest, sw.js, icons/...).
3. Repository → Settings → Pages → Source: "Deploy from a branch" → Branch: `main` / `(root)` → Save.
4. After 1–2 minutes your app is at https://YOUR-USERNAME.github.io/rent-book/
5. On the iPhone, open that address in Safari → Share → Add to Home Screen → Add.
6. Open Rent Book from its icon. Go to Settings and enter tenant names, your name,
   the water price per tank and the starting meter readings.

Backups: Settings → Save backup (save the file to Files / iCloud Drive).
Restore: Settings → Restore backup.

Updating later: replace index.html in the repository and change the CACHE name in sw.js
(for example rent-book-v2) so phones pick up the new version.
