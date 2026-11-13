MARCEAU PWA files for GitHub Pages
=================================

Upload these files and folders into the ROOT of your existing repository
(the same folder that contains index.html):

- index.html
- manifest.webmanifest
- sw.js
- icons/ (all PNG files)

Your published site is under /marceauebook/, so all PWA paths are relative
and the manifest scope is ./.

After committing and publishing:
1. Open https://marceauapparel.github.io/marceauebook/
2. Refresh the page once or twice while online.
3. In Chrome, use the browser menu > Install app (or Add to Home screen).
4. If an old version is cached, clear the site's storage/cache and reload.

Note: The service worker caches the app shell for offline launch. Firebase
data synchronization still requires an internet connection.
