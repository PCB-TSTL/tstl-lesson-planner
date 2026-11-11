TSTL LESSON PLANNER — PWA v1.0

CONTENTS
- index.html
- manifest.webmanifest
- sw.js
- icons/

DEPLOYMENT
Upload the full contents of this folder to the root of an HTTPS site,
for example Netlify. Keep the folder structure unchanged.

INSTALLATION
PWA installation requires HTTPS or localhost. Opening index.html directly
with file:// is fine for inspection, but it will not register the service worker.

DATA
Student and lesson information is stored locally in IndexedDB.
The existing Export / Import Backup tools remain available.

OFFLINE
The application shell is cached by the service worker. Comfortaa is loaded
from Google Fonts and cached at runtime after the first successful online load.
System font fallbacks remain available if the font cannot be fetched.

VERSION
1.0.0

CUSTOM ICON
The supplied notebook SVG is used for the PWA, Apple touch icon and browser favicons.
