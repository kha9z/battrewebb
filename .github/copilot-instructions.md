# Copilot Instructions for Bättre Webb

This project is a simple static website for the "Bättre Webb" digital conference. It consists of a single HTML file (`index.html`), a CSS stylesheet (`index.css`), and two images in the `img/` directory. There are no build tools, frameworks, or external dependencies.

## Project Structure
- `index.html`: Main HTML file. Contains all markup for the site, including navigation, hero section, registration button, and information section.
- `index.css`: Stylesheet for layout, colors, and responsive design. Uses custom properties for button effects and flexbox for layout.
- `img/`: Contains `headerlogo.png` and `heroimg.png` used in the header and hero sections.

## Key Patterns & Conventions
- **Styling**: All styles are in `index.css`. Uses CSS custom properties for button glow effects. Responsive design is handled with media queries (incomplete in current file).
- **Navigation**: Internal navigation uses anchor links (`#information`, `#seminarier`, `#register`).
- **No JavaScript**: The site currently does not use any JavaScript. All interactivity is handled via HTML and CSS.
- **No Build/Deploy Workflow**: There are no build scripts, package managers, or deployment instructions. All files are static and can be served as-is.
- **Images**: All images are referenced with relative paths from the `img/` directory.

## How to Contribute
- Add new sections by editing `index.html` and updating styles in `index.css`.
- To add images, place them in the `img/` directory and reference them with relative paths.
- For new styles, follow the existing pattern of using flexbox for layout and custom properties for effects.
- If adding interactivity, consider keeping the site JavaScript-free unless necessary for accessibility or user experience.

## Example: Adding a New Section
1. Edit `index.html` to add a new `<div>` for your section.
2. Add a corresponding CSS class in `index.css` for styling.
3. Reference any images from the `img/` directory.

## References
- `index.html` and `index.css` are the primary files for all changes.
- No README or other documentation files exist yet.

---
For questions about project structure or conventions, review `index.html` and `index.css` for examples. If you add new patterns, document them here for future contributors.
