MY LIFE DASHBOARD - installable app
===================================

FILES (keep all in the same folder)
  index.html            the app
  manifest.webmanifest  app name, colours, icons
  sw.js                 offline support and updates
  icon-192.png, icon-512.png

INSTALL (free, using GitHub Pages)
 1. Create a new public GitHub repository.
 2. Upload every file from this zip to the repository root (not inside a sub-folder).
 3. Repository Settings > Pages > deploy from the main branch.
 4. After about a minute, open the https://...github.io/... address on your phone.
 5. iPhone: Safari > Share > Add to Home Screen.
    Android: Chrome menu > Install app.

MOVE YOUR EXISTING DATA
 In the old dashboard: Documents > Create backup, copy the text.
 In the new app: Documents > paste into the box > Restore.
 Later, use Save backup file / Restore from file to keep backups in Zoho WorkDrive.

UPDATING
 Replace index.html and sw.js in the repository with the new versions.
 The app picks them up next time it is opened online (Documents > App updates
 > Check for updates). Your data stays on your device.

PRIVACY
 Your data is stored only in your browser on your device. A public repository
 shows the app code, not your data. Do not put personal details in the files.
