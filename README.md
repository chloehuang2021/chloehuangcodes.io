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
