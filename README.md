# Mechanics Lab

A buildless interactive website for Applied Mathematics B154 and B224, based on the supplied Word layout. Open index.html in a browser to use it locally. No installation, external libraries or build step is needed.

## Included

- English and Afrikaans interface, module selection and demonstration access screens.
- Both module catalogues, chapter filters, topic search and placeholder problem pages.
- Original projectile, constant acceleration, fixed-axis rotation and undamped spring demonstrations with sliders, play/pause, reset and time scrubbing.
- Responsive styling and keyboard-accessible native controls.

## Publish on GitHub Pages

1. Create a GitHub repository, or use your chosen existing repository.
2. Upload the CONTENTS of this folder to the repository root. index.html must be at the root, alongside app.js, content.js, styles.css, .nojekyll and assets/.
3. In repository Settings > Pages, select Deploy from a branch, select main and /(root), then Save.
4. GitHub displays the published address in Pages settings after deployment. It usually follows https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/.

Official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

All application links and assets use relative paths or hash routing, including when hosted beneath a repository path. No workflow or package installation is required. This deliverable has not been uploaded to GitHub or published.

## Access screen

Prototype passwords: b154 and b224 (lowercase). Access is remembered for the browser session. Sign out clears both modules. Language preference is stored locally when browser storage is available.

These passwords are deliberately public demonstration values. JavaScript and content on GitHub Pages are downloadable and the screen can be bypassed. Do not put confidential material here. Real restricted course access requires authenticated hosting or a separate authenticated service.

## Editing course content

Edit content.js to change module names, chapters and topics. Each topic contains an English title, Afrikaans title, and optionally a concept-demo key (linear, projectile, rotation or spring). The simulation definitions and equations are in app.js; visual styling is in styles.css.

Problem numbers are intentional placeholders. Replace them and add course-specific demonstrations when the course content is ready. Duplicate buttons per topic are collapsed in this prototype. Placeholder pages explain that problems will be added later. The four working simulations are original concept examples, not Hibbeler solutions.

The particle illustration, gears and textbook cover were extracted from the supplied layout. No textbook problem statements or solutions were added.

## Verification

JavaScript syntax, successful HTTP serving and mocked-DOM functional checks passed for module access, incorrect passwords, catalogue rendering, no-result searches, and all four simulations' SVG output, time scrubbing and reset. The constant-acceleration diagram uses a fixed scale covering the full slider range. Browser rendering and mobile visual inspection could not be completed because the browser access host was unavailable. Review in desktop and mobile browsers before classroom use.
