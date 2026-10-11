NEXT UP - PWA package
=====================

Files
  index.html              the app
  manifest.webmanifest    name, colours, icons (makes it installable)
  sw.js                   service worker (makes it work offline)
  icon-192.png, icon-512.png, icon-maskable-512.png, apple-touch-icon.png

Put it online (pick one, all free)
  Netlify  : go to app.netlify.com/drop and drag the next-up-pwa FOLDER onto the page.
  Vercel   : vercel.com > Add New > Project > upload the folder (or push to GitHub).
  GitHub Pages: upload the files to a repo, then Settings > Pages > deploy from main branch.

The site must be served over HTTPS (all three above do this automatically).
Opening index.html straight from your computer will NOT install as an app.

Install on your phone
  Android (Chrome): open the address > menu (three dots) > Install app / Add to Home screen.
  iPhone (Safari):  open the address > Share button > Add to Home Screen.

Good to know
  - Your items are saved on that phone, in that browser. Another device starts fresh.
  - When you change any file, change CACHE_VERSION in sw.js (e.g. nextup-pwa-v2)
    so installed apps pick up the update.
