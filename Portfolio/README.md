# Akindehinde Omowumi Portfolio

A polished, responsive portfolio website for a no-code website designer and digital solutions specialist. The project is built with plain HTML, CSS, and JavaScript and does not require any package installation or build step.

## Overview

This portfolio showcases:
- A strong personal brand and headline section
- About and credentials sections
- Work/project gallery with filter buttons
- Service offerings and process workflow
- Client testimonials with profile images
- FAQ accordion and contact form section
- Dark and light theme toggle

## Project structure

- index.html — page structure and content placeholders
- styles.css — layout, typography, responsiveness, theme styles, and visual polish
- script.js — profile data, portfolio content, rendering logic, and dynamic interactions
- Asset/ — project previews, portraits, and brand visuals
- README.md — project documentation

## How to run locally

1. Open the project folder in your editor or file explorer.
2. Double-click index.html, or use a local static server if you prefer.
3. View the page in a browser.

No dependency installation is required.

## Customizing content

Most content is data-driven and lives in script.js:
- profile details and contact information
- project entries
- services and pricing
- process steps
- testimonials
- FAQ items

Update those arrays to change the portfolio without editing the HTML structure.

## Theme behavior

The site includes a theme toggle that:
- defaults to the system preference on first load
- switches between dark and light modes
- saves the user’s selection using localStorage

## Assets

The Asset folder contains:
- hero and portrait images
- project preview images
- testimonial client photos
- Squarespace and brand-specific mockup visuals

If you replace existing assets, keep the filenames consistent with the references in script.js.

## Hinting

Use these quick reminders when making future updates:

- Keep all content edits in script.js instead of hard-coding values into HTML.
- Preserve the supplied URLs, names, testimonials, pricing, and contact details unless a real update is required.
- Match image file names to the names used in the testimonial or project data to avoid broken portrait or preview references.
- Keep the black, white, lime, and deep olive brand palette consistent across new sections.
- Validate mobile layout and accessibility after adding new content or images.
- If a preview image is missing, check the Asset folder and update the corresponding filename or image source in script.js.

## Notes

- This is a static website and is designed for quick deployment.
- It is optimized for responsiveness and accessibility.
- The site is intended to be easy to update for future portfolio items, client reviews, and branding changes.
