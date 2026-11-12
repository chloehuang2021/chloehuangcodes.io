# ChloeHuangCodes — GitHub Pages migration starter

This is a **working static-site migration starter**, not a pixel-perfect copy. It reconstructs the six Wix page routes and core published text. The Wix media files, exact font families, spacing/animations, and contact form were **not recoverable** from the text-accessible site inspection.

## Publish
1. Extract all files to the root of `chloehuang2021/chloehuang2021.github.io`.
2. Commit to `main`; Pages is already configured to publish from main/root.
3. Browse `https://chloehuang2021.github.io` and check all links.
4. Replace the placeholder blocks with originals from the Wix Media Manager.
5. Download your resume PDF and save it as `assets/resume.pdf`; change the resume link on the Resume page to `/assets/resume.pdf`.
6. Recreate the Wix contact form with a third-party form service if you want form submissions; right now a working email link is supplied.
7. Compare desktop/mobile screenshots with Wix and adjust `style.css` until they match **before** changing DNS.

## Original paths recreated
- `/` About Me
- `/general-5/` Projects
- `/opsiq-ai-ticket-triage/`
- `/tiny-hoof-website/`
- `/covid19-ai-chatbot/`
- `/lead-collection/` Resume & Contact

GitHub Pages generally handles the trailing-slash directory index URLs; test links and redirects when publishing.

## Important
Do **not** cancel Wix Premium or change DNS yet. The resume link currently depends on Wix and the placeholders are not original website assets. Domain renewal is separate from Premium hosting.


## Screenshot-matched homepage update
The homepage has been rebuilt to follow the supplied full-page screenshots. Images ending with `-temp` are screenshot-derived temporary crops and MUST be replaced with the original Wix Media Manager images for a sharp, faithful design. The bird and footer icons are approximate text glyphs; replace with the original SVG/icon assets. Social-link URLs other than GitHub and email still need confirmation. Resume button currently opens Resume & Contact rather than downloading a PDF. Other pages retain their earlier draft styling.


## Original homepage image assets (new)
Original artwork supplied by the site owner is stored in `assets/chloe-avatar.png`, `cloud-banner.png`, `sun-icon.png`, and `paper-plane.png`. The Featured Projects section now uses owner-provided `opsiq-preview.jpg`, `tiny-hoof-preview.png`, `covid-chatbot-preview.png` and links to their individual pages.

The cloud footer background remains a temporary screenshot crop and the social symbols remain substitutes. Please supply the original footer background and social icons for a pixel-perfect match. The project screenshots were supplied as screenshots, not interactive demos. The visual arrangement is approximate.
