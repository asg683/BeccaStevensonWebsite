# Becca Stevenson — Website

A four-section, responsive personal website recreated from the supplied designs. Includes a soft fairy chime and sparkle animation on link clicks.

## Preview
Open `index.html` in a browser. Internet access is needed to load the optional Google Fonts; fallback fonts work offline.

## Publish on GitHub Pages
1. Create a GitHub repository.
2. Upload **the contents** of this folder (not the ZIP itself) to the repository root. Keep `index.html` at the top level.
3. In the repository, choose **Settings → Pages → Build and deployment → Deploy from a branch**.
4. Select **main** and **/(root)**, then **Save**.
5. Wait for GitHub Pages to provide the live site URL.

## IMPORTANT: Publication links
The screenshots show the *titles* of five articles but not their underlying URLs. Therefore, article links currently open a targeted Google search for the publication instead of pretending to link to the original article. In `index.html`, replace the five `href` URLs on links marked `data-work` with the exact article URLs when you have them. Internal navigation and the contact email already work.

## Files
- `index.html`: page content and links
- `styles.css`: appearance and responsive layout
- `script.js`: page switching, sparkle animation and synthesized fairy chime
- `assets/becca-photo.png`: cropped photo from supplied screenshot
- `assets/writing-preview.png`: cropped image from supplied screenshot

Sound plays only after a user clicks (required by modern browsers); it can be muted with the bottom-right button.

## Pink cursor
The site uses a custom pink arrow cursor matching `--pink` in `styles.css`. To change the pink, update the `fill` value in the SVG cursor at the end of `styles.css`.
