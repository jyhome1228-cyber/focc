# Cafe24 header/footer adaptation

GitHub `focc` branding adapted as Cafe24 Smart Design reusable templates.

1. Backup the active skin, especially `/layout/basic/header.html` and `/layout/basic/footer.html`.
2. Copy `layout/basic/header.html` and `layout/basic/footer.html` from this directory into the SAME Cafe24 paths.
3. Copy `layout/basic/css/focc-shell.css` to `/layout/basic/css/focc-shell.css`. The header template has the Cafe24 `<!--@css(...)-->` import directive.
4. Keep the existing `layout/basic/layout.html` including `<!--@contents-->`, shipping/payment modules and other CSS/JS directives unchanged.
5. Check the Cafe24 preview on desktop and mobile and test account/login, logout, search, cart, ordering, mobile menu, footer policies before publishing.

Notes:
- Logo SVG is served from the live GitHub Pages /focc/assets URL. For production reliability, upload the SVG to Cafe24 and replace its URL after validation.
- Perfume and Lifestyle currently route to Cafe24 categories 45 and 54; Press uses board 8.
- About Us and Global route temporarily to GitHub Pages, since equivalent Cafe24 pages were not supplied. Update them once Cafe24-native pages are ready.
- The underlying original Cafe24 header/footer were not provided, so integrations specific to them (language selector, custom search modal, shipping, cart count) are not reproduced.
- Seller business/legal contact information was copied from the public existing site; confirm before deployment.
- This folder is a staging adaptation; it does not change the current live store automatically.
