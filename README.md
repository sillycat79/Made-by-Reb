# Made by Reb — editable portfolio

## Open on your Mac
1. Double-click Made-by-Reb.zip to unzip it.
2. Move the Made-by-Reb folder to Documents or another location you prefer.
3. Double-click index.html to preview the website in your browser.
4. Open the folder in your code editor to make changes. Save, then refresh your browser.

No installation, npm, or build step is needed.

## Files
- index.html: bio, contact links, footer, four video cards and hidden results markup.
- styles.css: colours, fonts, responsive layouts and scrolling ticker.
- script.js: category filters and placeholder dialogs.
- assets/: put your photos and MP4 files here.

## Common edits
Change the bio: search for "Hi, I’m Rebecca" in index.html.
Change colours: edit the :root variables at the start of styles.css.
Change the coding portfolio link: search for "https://sillycat79.com/" in index.html and replace the URL with your live portfolio address if desired.

## Add actual video samples
Replace a card's <button class="video-frame" ...>...</button> with:
<video class="video-frame" controls playsinline preload="metadata" src="assets/video-1.mp4"></video>
Keep the surrounding article and its data-category so filters still work.
Repeat for all four cards. Update titles and descriptions and remove the coming-soon introduction when ready.

## Hidden results
The #results section is hidden using the .future-section class and aria-hidden="true".
Fill it with verified metrics, testimonials or brand partnerships before displaying it.
Remove any unused sections; then remove the future-section class and aria-hidden attribute.
Never publish placeholder metrics as real results.

## Upload to another host
Upload index.html, styles.css, script.js and assets together, retaining their relative paths.
For Cloudflare Pages direct upload, ZIP these website files with index.html at the archive root (or upload this folder).
https://developers.cloudflare.com/pages/get-started/direct-upload/
Cloudflare Pages has a 25 MiB limit per asset; larger videos need separate hosting or embeds.

Local edits do not automatically update the hosted ChatGPT site. Upload changed files to your chosen host, or share them in this chat for an update.
