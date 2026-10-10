# Porsche Sales Quote – SAP Sales Cloud V2 Mashup

Hebrew (RTL) car sales quotation form styled with SAP Horizon, built to embed as a mashup in SAP Sales & Service Cloud V2.

## Files
- `index.html` – self-contained app (fonts, icons, styles and logic inlined). Open directly in a browser or host on any static server.

## Features
- Quotation item list: #, קוד פריט, תיאור פריט, תמחיר tag, סה"כ, actions
- מספר קומיסיון field with Porsche Code link
- בחירת רכב: דגם/מלאי toggle, filters (דגם רכב, תת דגם, צבע), car list with select / info (double-click selects)
- Car details popup with image and option list
- הוספת פריט: manual row with searchable item picker; colour picker for colour-required items
- תוספת מקומית: local add-ons (₪ 3,200)
- נקה בחירה, discount (% / amount), VAT 18%, totals, הערות

## Hosting as a mashup
Publish `index.html` via GitHub Pages (Settings → Pages → Deploy from branch `main`, root) and register the resulting URL as a URL mashup in SAP Sales Cloud V2.

## Notes
All data is mock data. The default car image loads from Wikimedia Commons (Alexander-93, CC BY-SA 4.0) and requires internet access.
