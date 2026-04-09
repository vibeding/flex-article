# Project Claude: A Study in Flexbox

This project is a complete overhaul of a landing page originally centered on high-priced NFTs. I have pivoted the theme to focus on Claude, an AI collaborator, using this as a real-world scenario to practice and master CSS Flexbox.

---

## The Goal

The primary objective here was to build a layout that is both flexible and responsive. Instead of relying on legacy layout methods like floats or positioning, I used the Flexbox module to handle alignment, spacing, and the overall flow of the page.

---

## Technical Implementation

I focused on a few core Flexbox patterns throughout this build:

- **Header and Navigation:** Used `display: flex` and `justify-content: space-between` to separate the logo and the navigation links without needing manual margins.
- **The Hero Section:** Practiced centering content both vertically and horizontally to create a balanced entry point for the user.
- **Feature Grid:** For the multi-item sections, I implemented `flex-wrap: wrap`. This ensures that as the screen gets smaller, the content stacks naturally rather than breaking the layout.
- **Consistent Spacing:** Utilized the `gap` property within flex containers to maintain uniform distance between elements, which is much cleaner than managing individual margins.

---

## Project Structure

- **index.html:** The semantic structure of the site.
- **style.css:** The stylesheet where all the Flexbox logic resides.
- **images/:** A folder containing the visual assets used for the Claude theme.

---

## How to View the Project

You can view the site by opening the index.html file in any modern web browser. To see the Flexbox magic in action, open the browser's developer tools and resize the window to see how the containers respond to different viewport widths.

---

## Reflections

Moving from a satirical NFT site to a more refined AI-themed site required a shift in both visual style and code structure. The biggest takeaway was learning how much easier it is to manage complex layouts when you let Flexbox handle the heavy lifting of alignment.

---

**2026 Flexbox Practice**
