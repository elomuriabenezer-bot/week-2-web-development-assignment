# SpendWise Dashboard Shell — Week 4

A responsive static personal finance dashboard built for the PLP Week 4 assignment. It focuses on page structure and visual layout using CSS Grid and Flexbox. No JavaScript functionality is required for this task.

## Project files

- `index.html` — semantic page structure, sidebar navigation, header, account summary, six spending category cards, recent transactions and reminder panel.
- `style.css` — theme variables, CSS Grid and Flexbox layouts, card styling, responsive rules, micro-interactions and dark theme.

## Requirements covered

- CSS Grid controls the overall dashboard, summary cards, category cards and lower content layout.
- Flexbox arranges the sidebar navigation, header actions, card details and transaction rows.
- Theme colours are stored as custom properties in `:root`.
- At widths below 768px, the dashboard changes to a single-column layout and the navigation becomes horizontally scrollable.
- Category cards are keyboard-focusable and use a 200ms transform and shadow transition on hover and focus.
- A dark colour theme is included through `@media (prefers-color-scheme: dark)`.

## Run locally

1. Download or clone this repository.
2. Open the `week-4-dashboard` folder in VS Code.
3. Open `index.html` in a browser, or use the Live Server extension.
4. Resize the browser below 768px to check the mobile layout.

Google Fonts require an internet connection. The financial figures are sample static content for demonstration.
