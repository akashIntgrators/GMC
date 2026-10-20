# Projects — static map

No Google Maps key, billing, map ID or runtime map request is needed. The map PNG ships with the website. The only external requests are media URLs explicitly added by the editor.

Open admin.html, enter project names, latitude/longitude and media, save each project to the working list, then export projects-data.js. Replace that file in GitHub and upload local media under assets/. The editor is not a signed-in CMS; unpublished edits live only in the current tab until exported.

Pins use Web Mercator interpolation over documented image bounds: north 13.12, south 12.83, west 77.42, east 77.73. The original map's bounds are rounded, so pin placement is approximate and must be visually checked against known landmarks before using real sites. Not for navigation/survey. The map is from 2021 and may be outdated. Outside/invalid coordinates are not clamped into the map; the project stays in the selector with an outside-map label. To expand coverage, replace the map and update bounds together. Keep image aspect ratio and never crop the map independently of its pins.

Each pin and project-list button opens the same horizontal media tray. Images and direct video files are supported. Details remain hidden until selection. Replace sample projects and illustrative media before publishing.

## Attribution
Map: OpenStreetMap, uploaded/recentered by BanyanTea via Wikimedia Commons, 2021. PNG raster rendition of the original SVG. Base artwork unmodified; interactive project pins are a separate HTML overlay. Map asset and any adaptations supplied under CC BY-SA 2.0. Preserve visible attribution and license links.
Source: https://commons.wikimedia.org/wiki/File:India_Karnataka_Bangalore_Bengaluru_location_Map.svg
License: https://creativecommons.org/licenses/by-sa/2.0/
Data attribution: https://www.openstreetmap.org/copyright
