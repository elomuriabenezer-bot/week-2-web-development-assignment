# SpendWise — Personal Budget Tracker (Week 3)

SpendWise is a responsive personal budget tracker interface. This Week 3 update focuses on visual identity and CSS presentation while keeping the existing HTML structure and page content.

## Project files

- `index.html` — the existing page structure, including the page heading, budget overview, expense table, Add Expense form, help section, and budgeting video.
- `style.css` — the visual design: colour palette, Google Fonts, responsive layout, form and table styling, hover and focus states, and CSS Box Model spacing.

## Week 3 design choices

### Colour palette

- Primary teal: `#176B67`
- Dark teal: `#10524F`
- Soft mint: `#DDF3ED`
- Page background: `#F4F7F6`
- White cards: `#FFFFFF`

The colours are stored as CSS custom properties in `:root` so they can be reused consistently.

### Typography

- **Manrope** is used for headings and important titles.
- **DM Sans** is used for body text, labels, buttons, and table content.
- Both fonts are loaded from Google Fonts in the stylesheet, with sans-serif fallbacks.

### Expense table and form

The expense table has a clear header, padded cells, borders, alternating row colours, and a hover state. Form labels and controls use consistent spacing, rounded borders, and visible focus feedback. Buttons use the same teal theme as the rest of the page.

### CSS Box Model

The page heading, expense table, form, and supporting sections are visually separated using margin, padding, borders, border-radius, and subtle shadows. The global `box-sizing: border-box` rule makes element sizing predictable.

## Run the project

1. Clone or download this repository.
2. Keep `index.html` and `style.css` in the same folder.
3. Open `index.html` in a browser, or use Live Server in VS Code.
4. An internet connection is needed for Google Fonts and the embedded YouTube video.

## Functionality note

This assignment is focused on CSS visual design. The sample expenses are static, and the Add Expense button remains a placeholder as required by the current lesson scope. No new JavaScript functionality has been added.
