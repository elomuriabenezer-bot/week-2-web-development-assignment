# SpendWise — Personal Budget Tracker (Week 3)

SpendWise is a responsive personal budget tracker interface. This update focuses on the visual identity of the existing project. The original HTML structure and content are preserved; the improvements are made with CSS.

## Project files

- `index.html` — the existing page structure, including the page heading, budget overview, expense table, Add Expense form, help section, and budgeting video.
- `style.css` — the visual design, including the colour palette, Google Fonts, responsive layout, table and form styling, and CSS Box Model spacing.

## Design choices

### Colour palette

- Primary teal: `#176B67`
- Dark teal: `#10524F`
- Soft mint: `#DDF3ED`
- Page background: `#F4F7F6`
- White cards: `#FFFFFF`

The colours are stored as CSS custom properties in `:root` and reused across the page for a consistent appearance.

### Typography

- **Manrope** is used for headings and important titles.
- **DM Sans** is used for body text, labels, buttons, and table content.
- Both fonts are loaded from Google Fonts, with sans-serif fallbacks.

### Expense table and form

The expense table uses a clear header, padded cells, borders, alternating row colours, and a hover state. Form labels and controls have consistent spacing, rounded borders, and visible focus feedback. The Add Expense button uses the same teal theme as the rest of the interface.

### CSS Box Model

The heading, summary cards, expense table, form, and supporting sections are separated using margin, padding, borders, border-radius, and subtle shadows. The global `box-sizing: border-box` rule keeps element sizing predictable.

## Run the project

1. Clone or download this repository.
2. Keep `index.html` and `style.css` in the same folder.
3. Open `index.html` in a browser, or use Live Server in VS Code.
4. An internet connection is needed for Google Fonts and the embedded YouTube video.

## Functionality note

This assignment focuses on CSS visual design. The sample expenses are static, and the Add Expense button remains a visual placeholder. No new HTML structure or JavaScript functionality has been added.
