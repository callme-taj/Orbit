# ORBIT Website

Static GitHub Pages starter for a personal sci-fi space-themed hub.

## Pages
- `index.html` — Home
- `games.html` — Games
- `notes.html` — Notes (local browser storage)
- `files.html` — Files (local demo uploader)
- `social.html` — Social links
- `request.html` — Request center (local browser storage)
- `about.html` — About
- `login.html` — Optional Google-login integration placeholder

## Important architecture note
GitHub Pages is static hosting. It cannot, by itself, provide secure shared admin uploads, shared visitor requests, or real Google authentication. The included local features work on the current device/browser.

For real shared uploads + Google sign-in, connect Firebase Authentication, Cloud Firestore and Cloud Storage, or another backend. Firebase's current web docs recommend the modular JS SDK and document browser-module imports from the Firebase CDN. See the official Firebase web setup docs.
