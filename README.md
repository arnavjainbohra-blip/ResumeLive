# M Arnav Jain — Resume Website

A simple, responsive, single-page resume website made with HTML and CSS for the IIM Bangalore BBA Digital Business & Entrepreneurship Website Development assessment.

## Project structure

```text
arnav-resume-website/
├── index.html-
├── style.css
├── Arnav-Jain-Resume.pdf
└── README.md
```

## Run the website

1. Extract the ZIP file.
2. Open `index.html` in a browser.
3. The website uses local HTML, CSS and the supplied PDF. No external fonts, libraries or JavaScript are needed.

## CSS concepts used

- **Colour and typography:** A restrained green, off-white and charcoal palette with system fonts and serif headings.
- **Element selectors:** Global rules for `body`, headings, paragraphs and links.
- **Class selectors:** Reusable styles such as `.intro`, `.timeline-item`, `.role-item` and `.button`.
- **ID selectors:** Section IDs such as `#about`, `#education`, `#work`, `#leadership` and `#contact` are used by the navigation links.
- **Positioning:** The header uses `position: sticky`; the skip link uses positioning so it appears when keyboard-focused.
- **Display and layout:** Flexbox is used for navigation, links and contact details. CSS Grid is used for the hero, highlights and two-column sections.
- **Responsive design:** Media queries adapt the navigation, timeline and content layout for smaller screens.
- **Accessibility:** Semantic HTML, descriptive navigation labels, a skip link, keyboard focus styles and readable colour contrast.

## Publish with GitHub Pages

1. Create a new GitHub repository (for example, `arnav-resume-website`).
2. Extract this ZIP and upload the **contents** of the `arnav-resume-website` folder to the repository root. Keep `index.html` at the root level.
3. Commit the files to the `main` branch.
4. Open **Settings → Pages** in the repository.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Choose the `main` branch and the `/(root)` folder, then save.
7. GitHub Pages will show the published website URL in the Pages settings.

## Editing the website

- Edit `index.html` to change the text and sections.
- Edit `css/style.css` to change colours, spacing, typography and layout.
- Keep the `assets` folder alongside `index.html` so the resume PDF link continues to work.

## Before publishing

Check that the contact details and all resume information are correct and that you are comfortable making the phone number and email address public.
