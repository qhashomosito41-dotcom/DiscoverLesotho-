# Discover Lesotho Adventures

A responsive, static tourism landing page created as a student project for the DIWT2112 Web Technology Group Assignment.

## Project overview

The fictional brand introduces visitors to Lesotho-inspired travel experiences, destination ideas, sample tour packages, and an enquiry form demonstration.

**This is a student demonstration website, not a real travel company.** Package ideas and testimonials are illustrative. Social media accounts are not configured. The enquiry form validates information in the browser but does not send or save it.

## Technology

- HTML5 for semantic content and page structure.
- CSS3 for visual design, layout, responsive breakpoints, motion preferences, and all interactions.
- No JavaScript. The mobile menu and testimonial controls use CSS-only techniques (`:target` and radio inputs), and the form uses native HTML5 validation.
- No framework or build process is required.

## Run locally

1. Download and extract the project folder.
2. Open `index.html` in a modern browser.

For a more realistic local server, use one of these options:

- VS Code with the Live Server extension.
- Python installed locally: run `python -m http.server 8000` from the project directory, then open `http://localhost:8000`.

The site is static; no database, server-side language, or package installation is required.

## Project structure

```text
discover-lesotho-adventures/
├── index.html
├── README.md
├── builder-selection.md
├── presentation-outline.md
├── css/
│   └── style.css
├── assets/
│   ├── icons/
│   │   └── favicon.svg
│   ├── images/
│   └── videos/
└── docs/
    ├── deployment-guide.md
    └── testing-checklist.md
```

## Replacing images

All images are stored locally in `assets/images/`, so no internet connection is required to load them. They were originally sourced from Unsplash; before final submission, check that each image's use complies with the source's current licence and attribution terms.

To replace an image, find its `<img>` element in `index.html` or the hero `background-image` rule in `css/style.css`. Add the replacement image to `assets/images/` and update the path. Use descriptive alt text for informative images.

The images are illustrative and may not depict the exact Lesotho destinations named in the copy.

## Branding and content

Update the brand name, colour variables near the top of `css/style.css`, copy, destination descriptions, and navigation labels as required by your group. Keep the fictional-project notice unless the project is transformed into a real service with verified information.

## Enquiry form limitations

The form uses native HTML5 validation (`required`, `type="email"`, and `minlength`) to check the name, email address, and demonstration consent in the visitor's browser. Form fields have no `name` attributes and the form posts to a fragment, so it deliberately does **not** submit data to an external server, send email, or save personal information. A CSS-only confirmation message appears after a valid submission.

To support genuine enquiries in a future real project, configure a backend or a reputable form-processing service, review its privacy and security requirements, update the privacy notice, and test delivery. Do not add real personal data to this demo.

## Builder / development approach

See `builder-selection.md` for the rationale and trade-offs of using custom HTML and CSS instead of a drag-and-drop builder.

## Free hosting

See `docs/deployment-guide.md` for GitHub Pages and Netlify deployment instructions.

## Before submission

- Replace or confirm project details with your group.
- Test every link, button, image, and form state.
- Review the `docs/testing-checklist.md`.
- Confirm the public URL works on another device or in a private browser window.
- Prepare the presentation using `presentation-outline.md`.
- Ask the lecturer how the website-builder criterion applies to a fully custom-coded site and clarify the Courier New, size 9 print requirement.

## Accessibility and performance notes

The page includes semantic landmarks, a skip link, visible focus states, a keyboard-operable mobile menu, labelled form fields, alt text, lazy-loaded below-the-fold images, and reduced-motion support. Run your own browser and accessibility checks before submission.
