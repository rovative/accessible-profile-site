# Accessible Profile Site

A personal portfolio site built with semantic HTML, CSS, and vanilla JavaScript, with a focus on front-end fundamentals and web accessibility.

## Overview

Originally created as a university assignment for the accessibility and usability module of my BSc Computer Science degree at the University of Hertfordshire. The project has since been redesigned as a professional portfolio piece. The original focus on accessibility has been preserved and strengthened throughout the redesign.

The site is intentionally built without a framework — demonstrating that clean, accessible, performant web experiences don't require complex tooling.

## Features

- Responsive layout (mobile-first, tested at all screen sizes)
- Keyboard-navigable interface with visible focus states
- Skip-to-content link for screen reader and keyboard users
- Semantic HTML5 landmarks throughout (`header`, `main`, `nav`, `section`, `article`, `footer`, `aside`)
- `prefers-reduced-motion` support — animations and transitions disabled when requested
- Accessible mobile navigation with `aria-expanded` state and Escape-to-close
- Native `<details>` / `<summary>` for project descriptions — works without JavaScript
- Sufficient colour contrast (WCAG AA)
- Descriptive alt text on meaningful images; empty `alt=""` on decorative ones
- No unnecessary ARIA — semantic HTML used where it does the job

## Technologies

- HTML5
- CSS3 (custom properties, Grid, Flexbox, media queries)
- Vanilla JavaScript (mobile nav toggle, dynamic year)

## Running locally

No build step required. Open `index.html` directly in a browser, or serve with any static file server:

```bash
npx serve .
# or
python -m http.server
```

## Project background

Built in 2024 as part of my Computer Science degree at the University of Hertfordshire. The portfolio section links to two projects from that period — a weather application and a BMI/water tracker — both available under the original university GitHub account ([rf23aam](https://github.com/rf23aam)).

## Author

Robert Florea  
[github.com/rovative](https://github.com/rovative)
