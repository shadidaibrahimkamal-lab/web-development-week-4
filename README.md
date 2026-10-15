# SpendWise Dashboard Shell

This project is a static dashboard prototype for a personal finance application called SpendWise. It focuses on a clean, modern layout built with CSS Grid and Flexbox, without adding interactive functionality.

## What is included

- A left sidebar navigation and a top header for the dashboard shell.
- Six category cards showing realistic spending categories: Food, Transport, Rent, Entertainment, Savings, and Utilities.
- A responsive layout that collapses to a single-column structure below 768px.
- CSS custom properties for a consistent design system using a theme that can be updated easily.
- Hover and focus motions on dashboard cards and buttons with short, subtle animations.
- A dark-mode theme using the `prefers-color-scheme: dark` media query.

## File structure

- `index.html` – The dashboard structure and static content.
- `style.css` – All layout, theme, responsive, and animation styling.

## How the layout works

- The page uses CSS Grid to organize the full dashboard shell and card grid.
- Flexbox is used for the header actions, navigation items, and each finance card structure.
- The design stays mobile-friendly by adjusting the grid and sidebar layout for narrower screens.

## Design notes

The dashboard uses a clean blue-and-orange brand palette with emphasis on hierarchy and readability. The colors are defined in `:root` and reused throughout the CSS to make maintenance straightforward.
