# Mei Wong | Software Developer Portfolio

A responsive, single-page portfolio website for a fictional software developer, Mei Wong. Built as the Bootstrap walkthrough project for the Code Institute Full Stack Software Development course.

## About the project

This site was built step by step following Code Institute's Bootstrap module. It shows how Bootstrap's grid and components can create a responsive layout with very little custom CSS, and how custom CSS can then override Bootstrap's defaults to give the site its own look.

Mei Wong and all project content are fictional and supplied by Code Institute.

## Features

- **Navbar:** responsive navigation that collapses into a toggle menu below 576px, with links to each section.
- **Hero header:** introduction to Mei, a background image and a "Subscribe to my newsletter!" button.
- **Newsletter modal:** a pop-up sign-up form (name and email) that opens without leaving the page.
- **About section:** photo and biography side by side on medium screens and up, stacked on mobile.
- **Portfolio section:** four project cards in a responsive grid, one column on mobile and two from medium screens up.
- **Contact form:** full name, phone number, email and message fields, laid out three across on large screens.

## Customisations

- Custom colour palette and Google Fonts (DM Serif Display for headings, Poppins for body text).
- A reusable `sharp-corners` class that removes Bootstrap's rounded corners from an element and everything inside it.
- A reusable `custom-button` class for consistent button colour and hover effect.
- Section-scoped overrides (for example `#portfolio .card-title`) so changes do not leak into other Bootstrap components.
- A media query at Bootstrap's XL breakpoint (1200px) to keep portfolio card heights even.

## Technologies used

- HTML5
- CSS3
- [Bootstrap 5.3](https://getbootstrap.com/docs/5.3/) (CSS, plus Bootstrap's JavaScript bundle for the navbar toggle and modal; no custom JavaScript)
- [Google Fonts](https://fonts.google.com/)
- VS Code with the Live Server extension

## Credits

- Project brief, content, images and walkthrough: [Code Institute](https://codeinstitute.net/)
- Layout components: [Bootstrap documentation](https://getbootstrap.com/docs/5.3/)
- Fonts: DM Serif Display and Poppins via Google Fonts
