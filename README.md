# Eugene Kirdzei — standalone website

Double-click **index.html** to open the website in a current Chrome, Edge, Firefox, or Safari browser. No installation, server, build command, or internet connection is needed to view the site.

Keep this folder together when copying or sharing it. The files can also be uploaded directly to ordinary static hosting.

## Included

- The full résumé, timeline, Top Skills, and current PDF download.
- Light/dark themes, About Me photo cards, contact options, company tooltips, highlights, and the floating Contact Me button.
- The animated background shader and draggable desktop badge. Fonts, textures, model geometry, and the physics engine are bundled locally. Mobile still hides the badge.
- Readable HTML content and a working PDF link even with JavaScript disabled.

## Notes

- WebGL/hardware acceleration is needed for the decorative 3D badge and shader. The résumé remains available without WebGL.
- Phone/email links use your configured apps. GitHub, LinkedIn, messaging services, and other external links need internet access.
- Some browsers do not save theme preferences for local files; switching themes still works during the current visit.
- No analytics, server APIs, CDN scripts, or runtime package downloads are required.
- Source website: https://eugene-kirdzej.vercel.app/

This folder is an independent snapshot; changing it does not change the hosted website. The optional exporter lives next door in **static-site-source/** and uses the original site's installed build dependencies.
