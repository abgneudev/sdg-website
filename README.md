# SDG Website

## Overview

This project is a multi-page website about an animal of choice, created to demonstrate HTML, CSS, and responsive design skills. The website consists of multiple HTML pages and related CSS to structure and style the content.

Video Walk through: [[(Video)](https://drive.google.com/file/d/1ajrwoKQbtrYTP1wBSnNDW3rXulznS7f6/view?usp=sharing)]

## How to Run the Website

To view and use the website:

1. Install necessary dependencies (only required once on any given computer):
   ```bash
   npm install
   ```
2. run `node server.js`
3. Access the website on your `http://localhost:3000/`

## Website Structure

The website contains the following pages, located in the `public/` directory:

- **index.html**: Homepage
- **about.html**: About page
- **register.html**: Registration page

Each page is structured with a `<header>`, `<main>`, and `<footer>` section in semantically correct HTML. All pages have titles and consistent navigation links.

### Header/Footer

- The header and footer are identical across all pages, with the exception of page-specific identifiers in the `<h1>` or `<h2>`.
- The header contains a logo image, which links back to the homepage.
- The header and footer have a distinct background color, separate from the main content.
- Each logo includes an `alt` attribute describing the image for accessibility.

### Navigation

Each page includes a navigation menu (`<nav>`) with the following links:

- **Menu**: Links to:
  - Home
  - About
  - Register
- **External Links**: Links to at least 3 actual pages on the internet (e.g., Wikipedia pages).

The navigation can be displayed as either:

- A horizontal menu with dropdowns
- A vertical menu with slide-in/slide-out behavior

## Page-Specific Content

### Homepage (index.html)

- Contains at least 3 UI Cards, each with:
  - A heading title
  - A call-to-action link
  - A unique background color or image to visually differentiate each card

The homepage prominently displays the animal the site is about.

### About Page (about.html)

- Includes at least 3 paragraphs of text, each with at least 3 sentences.
- At least 1 paragraph contains real information about the chosen animal.

### Registration Page (register.html)

- Contains a form that submits via POST to `/register`.
- The form includes:
  - Name and email fields
  - A checkbox and a dropdown selection
- At least one field is required and clearly marked as such.
- The form layout follows a 1 or 2-column design and is usable across required viewport sizes.

## Responsive and Adaptive Design

- The website layout follows a 12-column grid system.
- The website is readable and responsive on screens as small as 360px, with text wrapping and adaptive breakpoints.
- Uses `rem` units for breakpoints and responsive text, ensuring content remains accessible at varying screen sizes.

## Accessibility

- All interactive elements are keyboard-accessible.
- Color differences alone do not convey information.
- All form fields are labeled, and required fields are marked with text.
- Images have descriptive `alt` attributes for screen readers.
- Icons only enhance the experience and are not necessary for understanding.

## Demonstrated Skills

This project demonstrates knowledge of:

- Box Model
- Semantic HTML
- Semantic class names
- CSS Grid and Flexbox
- 12-column grid layout
- Responsive and adaptive HTML design
- HTML Forms

## Additional Constraints

- **No JavaScript**: Only HTML and CSS are used for this project.
- **No float-based layouts**: Floats are only used when wrapping text around images.
- **No tables or iframes**: Except when displaying tabular data (not required in this project).
- **No CSS preprocessors**: Only vanilla CSS is used.
- **Image Restrictions**:
  - All images are either owned by the creator or sourced from [Unsplash](http://unsplash.com).
  - Images from Unsplash are downloaded and their URLs are listed in `licenses.txt`.
  - All images have descriptive `alt` text for accessibility.

## License Information

For images from [Unsplash](http://unsplash.com), a `licenses.txt` file lists the URLs of images used. For any personally owned images, filenames are listed in `licenses.txt` as well.
