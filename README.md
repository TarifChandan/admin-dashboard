# Admin Dashboard

A responsive Admin Dashboard built primarily with CSS Grid, as a project for The Odin Project curriculum. This project focuses on mastering complex layout techniques using modern CSS.

## 🚀 Live Preview

## 📐 Layout Structure

The dashboard is built with a multi-tiered grid system:

1. **Primary Layout (Page-Level):**

   - A 2-column grid with a fixed-width sidebar for navigation and a flexible main content area.

2. **Main Content Area:**

   - A 2-row grid for the header and the main body content.

3. **Main Body Section (Core Challenge):**

   - A **2x2 grid** where:
     - The `Your Projects` section spans both rows and takes **2/3** of the width.
     - The `Announcements` and `Trending` sections are placed in the right column, each taking one row and **1/3** of the width.

4. **Nested Grids:**
   - `Your Projects`: Uses a responsive grid with `repeat(auto-fit, minmax(...))` to create a fluid 2x3 layout for the project cards.
   - `Announcements` & `Trending`: Use internal grid/flexbox structures to maintain their content and height ratio relative to the main projects section.

## Learning Outcomes

Through this project, I successfully practiced and demonstrated:

- Planning and implementing complex layouts with CSS Grid.
- Creating nested grid structures within parent grid items.
- Using the `grid-template` and `grid-area` properties to define layout areas.
- Leveraging advanced grid features like `minmax()` and `auto-fit` to build responsive grids without media queries.
- Effectively combining CSS Grid for macro-layout and Flexbox for micro-layout.

##

**Disclaimer:** This project was assigned by The Odin Project. The design and concept are part of their curriculum.
