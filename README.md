# MyBike — landing page

A responsive single-page landing for **MyBike** electric bikes, built from a design mockup using the BEM methodology with SCSS and bundled with Vite.

## Demo

- [DEMO LINK](https://redfield-mp.github.io/landing-page/)

## Technologies

- HTML5 (semantic markup, BEM)
- SCSS (variables, mixins, modular structure)
- Vite — dev server and build
- Stylelint, Prettier, LintHTML — linting and formatting
- Cypress — e2e tests

## Features

- Responsive layout (mobile, tablet, and desktop)
- Burger menu for mobile devices (via `:target`, no JS required)
- Sections: Hero, About, Compare Bikes, Details, Contacts
- Contact form
- Interactive states (hover, focus) for links and buttons

## Structure

```
src/
├── images/        # images and icons
├── scripts/       # JavaScript
└── styles/        # SCSS partials and the main main.scss
index.html         # page markup
```

## Getting started

```bash
# install dependencies
npm install

# start the dev server
npm start

# build for production
npm run build

# run linters and tests
npm test
```