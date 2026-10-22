SCREENRAIL — COMPLETE WEBSITE, READY TO UPLOAD

All website code and assets are included. No framework, installation,
server code, database, API keys or build command is required.

UPLOAD TO YOUR OWN WEBSITE
1. Extract this ZIP.
2. Upload the files directly into your website's public folder.
3. index.html must be in that folder, alongside all the image files and
   manifest.webmanifest. Keep the filenames unchanged.
4. Open the website address in your browser.

All asset paths are relative, so this works at a domain root or in a subfolder.
For a host that accepts ZIP uploads, upload this ZIP if that is supported.
For a host that accepts folders, select the extracted folder.

GITHUB PAGES
1. Put the extracted files in the root of your repository.
2. In Settings > Pages, select deployment from a branch, then your branch
   and the root folder.
3. Visit the website URL shown by GitHub after publication completes.

IPHONE HOME SCREEN
1. Open your hosted HTTPS website in Safari.
2. Tap Share > Add to Home Screen.
3. Enable Open as Web App if shown, then tap Add.
4. Open Screenrail using its Home Screen icon.
Remove and re-add an old shortcut if its name or icon remains cached.

LOCAL PREVIEW (OPTIONAL)
Open a terminal in the extracted folder and run:
  Windows with Python: py -m http.server 8000
  macOS/Linux with Python: python3 -m http.server 8000
Then open http://localhost:8000
Python is only used here to serve files for preview; the hosted site does
not require Python.

FILES TO EDIT
index.html: all layout, colours, text, CSS and JavaScript for both screens.
manifest.webmanifest: app name, icon and standalone launch settings.
icon-r-v2.jpeg: current iPhone Home Screen icon.
screenrail-portrait.jpg: portrait shown on the second screen.
screenrail-pattern.png: decorative code at bottom left.
screenrail-emblem.png: SR logo at bottom right, with transparent background.
screenrail-pattern.svg: original vector source for the decorative code.
Other PNG files: earlier trial icons, retained for completeness.

The image positions are controlled by .pass-pattern and .pass-emblem in
index.html. Replace the corresponding PNG files to change those graphics.
Use View Pass to open the second screen and the x to return.
Append #pass to the page URL to open the second screen directly.

ABOUT THE EXPORT
This is the complete latest website with both PNG graphics.
The private ChatGPT sign-in on the original hosted URL belongs to that
hosting service and is not part of this code. Your copy uses your chosen
host's access settings.
Screenrail is fictional film branding. Its code is decorative and its
SR-PROP-001 number is a prop identifier, not a travel credential.
