# Personal Portfolio Website

## Project overview
This is a four-page personal portfolio built with HTML5 and CSS3 for a course assignment. It uses semantic HTML, a dark navy and teal colour palette, responsive stylesheets, and a native HTML contact form.

## Pages
- `index.html` — home page and navigation.
- `about.html` — biography, personal photo, and introduction video.
- `projects.html` — descriptions of coursework projects.
- `contact.html` — contact details and a form with browser-based validation.

## Folder structure
- `css/mobile.css` — shared base styles and mobile rules.
- `css/tablet.css` — tablet-specific layout overrides.
- `css/laptop.css` — laptop/desktop-specific layout overrides.
- `images/` — personal photo and video poster image.
- `videos/` — personal introduction video.

## Responsive design
The site uses fluid widths and CSS media queries. Flexbox is not used.

- **Mobile:** up to 600 CSS pixels. A single-column layout and compact navigation fit narrow screens.
- **Tablet:** 601–1024 CSS pixels. The layout uses two columns where there is enough room, while maintaining readable spacing.
- **Laptop/desktop:** 1025 CSS pixels and above. The content is centered with a maximum width of 1160 pixels; project and feature areas use multiple columns.

The three stylesheets are linked in each HTML file in this order: mobile, tablet, laptop. The mobile stylesheet contains base styles; the other stylesheets apply overrides only at their viewport breakpoints.

## Colour scheme
The design uses a dark navy and teal palette:
- Navy background: `#0b1728`
- Dark header: `#091321`
- Panel background: `#122238`
- Teal accent: `#35d0c2`
- Main text: `#edf5fb`
- Muted text: `#b6c7d6`

The palette is intended to create a consistent, high-contrast technology portfolio. If your instructor requires a scheme created in Adobe Color, create/save your own scheme there and add its name or URL here.

## Gradients
- `css/mobile.css` includes a diagonal linear gradient on the home hero section: `linear-gradient(145deg, #14263d, #0b1728 72%)`.
- This uses an angle (`145deg`) to control the direction of the gradient.

## Personalization required before submission
1. Replace every `[Your Name]`, `[Your Program]`, and example email address with your own details.
2. Replace `images/replace-with-your-photo.jpg` with your own photo. Update the `alt` text to describe the actual photo.
3. Record a 45–60 second introduction video and save it as `videos/introduction.mp4`.
4. Replace or edit project descriptions so they accurately reflect projects you personally completed and your contribution to each.
5. Test the contact form and decide whether the `mailto:` approach is acceptable for your course. A static GitHub Pages site cannot process/store form submissions by itself. The current form uses native browser validation and attempts to open the visitor's configured email application.
6. Review all pages for spelling, accessibility, and content accuracy.

## Validation and testing log
Do not claim tests passed until you have run them. Record the date and outcome of each test below.

| Test | Tool | Date run | Outcome / issues fixed |
|---|---|---|---|
| HTML validation (all four HTML pages) | https://validator.w3.org/ | Not run yet | Add result here |
| CSS validation (all three CSS files) | https://jigsaw.w3.org/css-validator/ | Not run yet | Add result here |
| Link checking | https://validator.w3.org/checklink | Not run yet | Add result here |
| Spelling check | Your chosen spell checker | Not run yet | Add result here |
| Accessibility check | https://wave.webaim.org/ | Not run yet | Add result here |
| Responsive layout | Browser resizing / device emulation | Not run yet | Add result here |
| GitHub Pages deployment | GitHub repository Pages settings | Not deployed yet | Add live URL after publishing |

## External code and attribution
This project was drafted specifically as a starter for this assignment. No third-party code snippets have intentionally been copied into the project. If you add code from an external website, document the source URL, author (if known), the portion used, and what it does here. Also add comments beside the adapted code, and follow the course's 10% limit for external code.

## Version control plan
Make meaningful commits after each major stage. For example:
1. `Add initial four HTML page structure`
2. `Add shared theme and mobile styles`
3. `Add tablet and laptop responsive styles`
4. `Add personal photo and introduction video`
5. `Add project content and contact validation`
6. `Fix validation and accessibility issues`
7. `Finalize README and deploy with GitHub Pages`

Only use commit messages for the work you actually complete; do not create misleading history.

## Publishing with GitHub Pages
1. Create a **public** repository on GitHub.
2. Upload or push this project's files while preserving the folder structure.
3. In the repository, open **Settings → Pages**.
4. Select deployment from the `main` branch and the root (`/`) folder, then save.
5. Wait for GitHub to publish the site. Open the generated URL and test all four pages and assets.
6. Add the real published URL to this README after verifying it works.

## Notes
The personal photo and introduction video are intentionally not supplied because the assignment requires your own photo and a 45–60 second video. The project descriptions and personal text are editable examples; verify all of them before submitting.
