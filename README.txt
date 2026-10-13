DayFlow — Responsive Component Library

Project structure
- index.html: DayFlow home page plus component-library examples.
- about.html: About page.
- contact.html: Contact form.
- README.txt: Project notes and local run instructions.
- CSS/style.css and CSS/styles.css: responsive styling, components, dark mode, and focus states.
- images/: homepage illustration.
- js/: reserved for future JavaScript. The modal is CSS-only and does not require JavaScript.

Run locally
1. Extract dayflownewrepo.zip.
2. Open the dayflownewrepo folder in Visual Studio Code.
3. Open index.html in your browser, or use the Live Server extension.

Responsive breakpoints
- Mobile: one column.
- Tablet: two columns at 600px and wider.
- Desktop: three columns at 1000px and wider.

Components
- Form labels, text/email/number/date inputs, select dropdowns, textarea, submit and reset buttons.
- CSS-only modal controlled by a checkbox and labels (no JavaScript).
- Success and error alert/notification styles.
- System dark mode using prefers-color-scheme: dark.
- A visible Dark mode checkbox on Home, About, and Contact pages lets users manually switch to dark mode even if their system is in light mode.
- Skip link, semantic landmarks, visible keyboard focus, descriptive labels, and reduced-motion support.

Accessibility audit
The project has been improved for accessibility, but a Chrome Lighthouse audit has NOT been run in this environment. To verify:
1. Open index.html in Chrome.
2. Open DevTools > Lighthouse.
3. Select Accessibility and run the report.
4. Fix any findings and rerun until the Accessibility score is above 90.

Note: CSS-only modal styling does not provide full dialog focus management or Escape-key behavior; those usually require JavaScript. This project keeps the modal CSS-only as requested.
