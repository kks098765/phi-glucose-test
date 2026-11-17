PHI Glucose Phone Prototype v0.6

Contents: index.html, manifest.webmanifest, sw.js, icons.

This is a browser-based glucose journal intended for HTTPS hosting.
Camera/photo -> experimental in-browser OCR -> user confirms value/time -> local IndexedDB save.
The OCR library is loaded from jsDelivr when needed and may require internet.
It is not yet accurate across the Contour meter photographs; always check suggested readings.
Photos are not intentionally transmitted by the app, but the app loads OCR code from a CDN.
Never add your personal readings or photographs to the public hosting repository.

For GitHub Pages on GitHub Free, the repository must be public.
Create a new repository containing ONLY the five runtime files, then enable Pages from main/root.
Open the published https:// URL on iPhone Safari; Share > Add to Home Screen.

Note: Local data saved in the laptop file:// origin is not automatically carried to the hosted site.
Safari versus Home Screen storage may also be separate: use the installed app consistently.

This is a practical test prototype, not a medical decision tool.
