# Style Guide

This document outlines the primary color palette and typography used in the project, derived from `index.html` and its embedded styles/Tailwind CSS usage.

## Color Palette

### Brand & Accent Colors
- **Primary Accent (Dark Salmon):** `#E9967A` (Used for links, borders, key highlights, and text gradients)
- **Secondary Accent (Coral):** `#FF7F50` (Used in gradients, theme color, and animated titles)
- **Gradient Tones:**
    - `#DEB887` (Burly Wood - used in various gradients)
    - `#F5DEB3` (Wheat - used in various gradients)
    - `#FFA07A` (Light Salmon - used in animated titles)
    - `#FF8C00` (Dark Orange - used in animated titles)
- **Call-to-Action Blue:** `#007bff` (Used for specific buttons and modal elements)
- **Call-to-Action Blue (Hover):** `#0056b3` (Darker blue for hover states)

### Neutral & UI Colors
- **White:** `#ffffff` (Backgrounds, text on dark elements)
- **Black:** `#000000` (Specific design elements)
- **Dark Text (Gray-900 equivalent):** `#1a202c` (For primary headings and text)
- **General Text (Gray-700 equivalent):** `#4a5568` (For general body text)
- **Secondary Text (Gray-600 equivalent):** `#718096` (For less prominent text)
- **Light Background (Orange-50 equivalent):** `#fffaf0` (For light section backgrounds)
- **Very Light Gray (Gray-50 equivalent):** `#f9fafb` (For very light backgrounds)
- **Star Rating:** `#facc15` (Tailwind `yellow-400`)

*Note: The project extensively uses Tailwind CSS, which provides a wide range of utility colors (e.g., `orange-100` to `orange-500`, `amber-50` to `amber-500`, `blue-100` to `blue-600`, various `gray` shades). The colors listed above represent the most prominent and explicitly defined shades.*

## Typography

### Font Families
- **Primary Sans-serif:** `'Poppins', sans-serif` (Used for body text and general UI elements)
- **Secondary Serif:** `'Playfair Display', serif` (Used for headings and more decorative text)
- **Monospace:** `'Courier New', monospace` (General guideline for code snippets, not explicitly used in `index.html`)

### Font Weights (Used in Poppins import)
- Light: `300`
- Regular: `400`
- Medium: `500`
- Semi-bold: `600`
- Bold: `700`

### Font Sizes & Line Heights (Examples from CSS, relative units are common)
- **H1:** `3rem` to `6rem` (e.g., `48px` to `96px` depending on screen size)
- **Body Text:** `1rem` (e.g., `16px`)
- **Line Heights:**
    - Headings: `1.2`
    - Body Text: `1.6`
