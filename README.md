# Zion Furniture – Static HTML & CSS Website

This project is a fully static, responsive furniture store website designed for future expansion. It uses only HTML5 and CSS3, with no JavaScript and no frameworks.

## Structure

- `index.html`  
  Home page featuring the hero section, featured products, and category links.

- `products.html`  
  Product listing page that displays a grid of furniture cards with static content.

- `about.html`  
  Brand story page outlining the studio’s mission, design philosophy, and craft.

- `contact.html`  
  Contact page with a static, accessible form layout and showroom contact details.

- `css/styles.css`  
  Global design system: color variables, typography, buttons, cards, and shared UI elements.

- `css/layout.css`  
  Layout rules for header, hero, sections, grids, footer, and the contact form.

- `css/responsive.css`  
  Responsive behavior using media queries for mobile, tablet, and desktop breakpoints.

- `images/placeholder-images/`  
  Directory intended for storing product and lifestyle placeholder images. Filenames referenced in HTML (for example `sofa-1.jpg`) can be added here later.

## Design System

- Neutral palette built from warm grays and soft neutrals.
- Single font stack: `Arial, Helvetica, sans-serif`.
- Reusable card and button components across all pages.
- Grid-based product and category layouts for a showroom-like appearance.

## Running Locally

1. Open the `zion-furniture` folder.
2. Double-click `index.html` to open it in your browser, or
3. Serve the folder with any static file server and visit the root URL.

## Adding JavaScript Later

- Navigation and layout are structured so that JavaScript can be attached unobtrusively:
  - Buttons use standard elements you can enhance with click handlers.
  - Product cards can host future interactions such as modals or cart actions.
  - Forms can have validation and submission logic added without changing the markup.

You can introduce JavaScript later by adding a separate script file and wiring interactions with progressive enhancement, keeping the underlying HTML accessible and functional.

