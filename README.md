# Mohak Garg — Personal résumé

A responsive HTML and CSS résumé for the IIMBx Website Development assignment.

Live website: https://mohakepsilon-pixel.github.io/mohak-resume/

## What the page contains

- A name, student tagline, school photograph, and short profile summary.
- Current BBA studies at IIM Bangalore and verified Class XII and Class X education.
- HTML, CSS, and GitHub skills described as developing skills.
- The 99 Percentiler web project and the résumé coursework project, with descriptions, tools, and working links.
- A GitHub contact link.

The site does not claim employment, certifications, grades, user counts, or sole authorship of the larger project. Private educational documents and learner identifiers are excluded from the public source.

## Files and preview

The browser-ready files are `index.html`, `styles.css`, `assets/favicon.svg`, and `assets/mohak-portrait-v2.jpg`. There is no build step, package installation, framework, or JavaScript requirement.

Open `index.html` in your browser, or run `python -m http.server 8000` from this checkout and visit `http://localhost:8000/`. GitHub Pages publishes the repository root from the `main` branch.

## How the code works

1. `header`, `nav`, `main`, `section`, `article`, `figure`, and `footer` give the content a semantic structure.
2. Element selectors set type and spacing defaults. Classes such as `.container`, `.resume-section`, and `.project-entry` style reusable layouts. IDs identify the navigation destinations and the contact section.
3. Grid aligns the profile and résumé sections. Flexbox aligns the navigation, dates, and action links. Margin, padding, borders, width, and line height control the box model and visual hierarchy.
4. A media query at 760px adapts the profile, navigation, and section columns for smaller screens. Navigation uses ordinary anchor links and works without JavaScript.
5. Hover and keyboard-focus states make links clear. A skip link, meaningful photo alt text, motion-free navigation, and a separate print stylesheet support different ways of using the page.

The matte black (`#101112`), graphite (`#191c20`), and silver (`#eeeeef`) palette uses a readable Arial/Helvetica font stack. The source is formatted and commented for review and learning.

## Course alignment

The site was reviewed against the course's résumé lesson (3.22), HTML lessons, CSS lessons, Flexbox/Grid examples, and responsive-design lessons. The school photograph was prepared from an existing photo by removing its printed label using the image-editing tool.

Reference code supplied through the course: https://github.com/shenoy-lab/DBE_Website_Development_Reference_Code

The assignment PDF is a separate private deliverable containing the live link, repository link, and design explanation. The student should review the résumé facts and understand the implementation before submission.
