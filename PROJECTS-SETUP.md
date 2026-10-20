# Projects setup

Open admin.html to add/edit site names, latitude, longitude, status and media. Save each project, then download projects-data.js and replace that file in GitHub. Edits are in memory until exported. This is not authenticated admin or a live CMS. GitHub repository write permissions control publication. Do not store secrets or private construction-site details in this public data file.

Add JPG/WebP photographs and MP4/WebM video files under assets/ (or use direct HTTPS media URLs). Enter one item per line: image | assets/site/photo.webp | caption. Keep clips compressed for mobile. Each project can contain multiple media items. The media tray scrolls horizontally and video has playback controls; nothing autoplays.

Without a key: the section shows clearly labelled sample project selectors, not a real or geographically accurate map. Replace sample sites and sample imagery before publication.

To activate Google Maps later:
1. Enable Maps JavaScript API in a billing-enabled Google Cloud project.
2. Create a browser API key restricted to the Maps JavaScript API and your production website referrer, https://gmc.techiwithhelmet.com/*. Configure a separate local test restriction/key if needed. Browser keys are visible to visitors by design; never use an unrestricted key.
3. Create a JavaScript map ID. DEMO_MAP_ID is testing-only.
4. Enter key and map ID in editor and export projects-data.js.
5. Upload the new JS files, data, HTML/CSS and media to the GMC repository. Test map loading, all pins, media playback and mobile scrolling.

Reference: https://developers.google.com/maps/documentation/javascript/advanced-markers/start

A real signed-in admin saving instantly for every visitor needs a backend/CMS and access control. It is not provided by static GitHub Pages. Current editor deliberately requires a reviewed GitHub commit to publish.

Implementation verification: source syntax checked; no live Google Maps key or API test performed. Sample media is proposal illustration; real project videos are pending.
