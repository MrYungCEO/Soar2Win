# Project Planning for Soar2Win Coaching Website

## Architecture Overview
The website is a static HTML site, primarily using Tailwind CSS for styling and some custom CSS for animations and specific components. JavaScript is used for interactive elements like mobile menus, modals, and scroll-reveal animations.

## Goals
The primary goal is to rebrand and reposition Soar2Win Coaching as "THE expert for successful women who struggle with self-doubt," focusing on the "Unmute Your Power" program and the P.O.W.E.R. framework. This involves significant content and navigation updates to the existing `index.html` and the creation of a new dedicated program page.

## Style and Constraints
- **Design:** Maintain the existing aesthetic, leveraging Tailwind CSS and the current color palette (orange, amber, earthy tones).
- **Responsiveness:** Ensure all changes are fully responsive and look good on various devices.
- **Performance:** Keep the site lightweight and fast.
- **Modularity:** While it's a static site, aim for logical separation of concerns within HTML sections and JavaScript functions.
- **No external frameworks/libraries beyond existing ones:** Stick to Tailwind CSS, Font Awesome, GSAP, and the current modal scripts.

## Key Positioning Changes
- **Target Audience:** Successful women who struggle with self-doubt.
- **Unique Methodology:** P.O.W.E.R. framework + Positive Intelligence.
- **Pricing:** Premium pricing ($8,500) for the 1:1 Intensive.

## Immediate Changes Summary
- Delete hero image (woman on beach) from `index.html` and replace with strong headline copy.
- Remove "Power of Coaching" section entirely from `index.html`.
- Remove "Why Work with a Certified Coach" section entirely from `index.html`.
- Replace current homepage copy with the provided P.O.W.E.R. framework version in `index.html`.
- Update contact form dropdown to focus on signature programs in `index.html`.
- Create a new dedicated page: "Unmute Your Power Program" (`unmute-your-power-program.html`) with detailed copy. This will be the main conversion page.
- Update website navigation:
    - Home
    - Unmute Your Power Program (main program page)
    - Work With Me (1:1, Group, Corporate options)
    - About
    - Resources/Blog
    - Contact

## Naming Conventions
- HTML files: `kebab-case.html`
- CSS classes: Tailwind CSS utility classes primarily, custom classes for specific animations or complex components.
- JavaScript: `camelCase` for functions and variables.

## Testing
- Manual browser testing for responsiveness and functionality after each major change.
- Verify all links and forms work correctly.
