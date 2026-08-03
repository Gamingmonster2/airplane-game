# R Drone Combat 3D | حرب الطائرات بدون طيار المطورة - PWA Deployment Guide

Congratulations! Your Progressive Web App package was successfully generated with **PWA Generator**.

## Package Structure
- `index.html` - Your original web application with injected PWA meta tags, manifest link, and Service Worker registration script.
- `manifest.json` - Web App Manifest defining application identity, colours, and icons.
- `sw.js` - Service Worker script implementing offline caching (cache-first strategy).
- `icon-192.png` - Standard PWA application icon (192x192).
- `icon-512.png` - High-resolution splash screen icon (512x512).
- `apple-touch-icon.png` - Apple iOS Home Screen icon (180x180).
- `favicon.ico` - Browser tab icon.

## Deployment Instructions
1. Upload all files to your web server root directory (e.g. `public_html` or `dist`).
2. Ensure your domain serves content over **HTTPS** (Service Workers strictly require secure origins or `localhost`).
3. Open Chrome DevTools -> Application tab -> Service Workers / Manifest to audit your PWA installation.
4. Test offline capabilities by toggling "Offline" mode in the Network tab.

Generated on 3 August 2026.
