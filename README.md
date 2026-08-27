# Responsive Menu Website

This website was generated from the uploaded 5-page menu PDF.

## Included
- 50 menu cards with the food photos extracted from the PDF
- Prices preserved from the PDF layout: 8,000៛ / 10,000៛ / 15,000៛ / 20,000៛
- Responsive layout:
  - Desktop: 3 columns
  - Tablet: 2 columns
  - Mobile phone: 1 column
- Search box
- Price filter
- Tap/click a food card to open a larger image
- Khmer-friendly font

## Run
Open `index.html` in a browser.

For VS Code, you can use Live Server for the best local development experience.

## Important
The PDF's embedded text is partially encoded/garbled when extracted programmatically, so the card names are placeholders (`ម្ហូបទី 01` ... `ម្ហូបទី 50`). Replace the names in the `menu` array inside `index.html` with the exact Khmer names if needed.
