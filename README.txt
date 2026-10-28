FlowMap by Structure and Flow - how to put it online (GitHub Pages) and install it

FILES (upload all of these, unzipped, to the same place):
  index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png, icon-maskable-512.png, apple-touch-icon.png

1. On github.com, create a new repository (for example "flowmap"). Public is fine.
2. Press "Add file", then "Upload files". Drag in the files above (the files, not the zip). Press "Commit changes".
3. Open the repository's Settings, then Pages. Under "Build and deployment" choose "Deploy from a branch",
   pick the "main" branch and the "/ (root)" folder, then Save.
4. Wait about a minute. Your app is at:  https://YOUR-USERNAME.github.io/flowmap/
5. Open that address on each device and install it:
   - PC (Chrome or Edge): press the install icon in the address bar, or open Settings (gear) in FlowMap and press "Install FlowMap".
   - Android: browser menu, then "Install app" (or "Add to Home screen").
   - iPhone: open in Safari, press Share, then "Add to Home Screen".

MOVING YOUR EXISTING MAPS
Maps are saved inside each browser, so the new web address starts empty. In your old FlowMap file open Settings (gear),
press "Backup all maps", then in the new app open Settings and press "Restore from backup". Do the same to move maps
between your PC and phone.

UPDATING
Upload the new files over the old ones (same names) and commit. Open the app while online and it refreshes itself.
If a device keeps showing the old version, change "flowmap-v1" near the top of sw.js to "flowmap-v2" (and so on).
