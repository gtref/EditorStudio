# SatisStudio MVP

## Goal

Create a simple, open-source online image editor focused on creating stickers, banners, and graphics.

The MVP should be lightweight, browser-based, and require no backend or database.

---

## Core Features

### Canvas

- Canvas for placing and editing elements
- Fixed-size canvas

### Images

- Upload images
- Render images on the canvas
- Move images around the canvas

### Text

- Add text elements
- Edit text
- Move text around the canvas

### Projects

- Save projects to a `.satis` file
- Open existing `.satis` files
- Import projects from disk
- Export projects to disk

### Export

- Export canvas as PNG

---

## Analytics

Use Microsoft Clarity to understand how the editor is used.

Track events:

- import-image
- add-text
- save-project
- open-project
- export-png

---

## Privacy

Include a cookie consent banner.

Example text:

> We use cookies and Microsoft Clarity to understand how people use SatisStudio, helping us improve the editor and prioritize new features. We do not sell your data.

Users should be able to:

- Accept analytics
- Decline analytics

Analytics should only load after consent.

---

## Open Source

- Source code available publicly
- Issue tracker available for bug reports and feature requests

---

## Not Included In MVP

- User accounts
- Cloud saves
- Database
- AI features
- Layers
- Filters
- Crop tools
- Drawing tools
- Collaboration
- Templates
- SVG export

---

## Tech Stack

- HTML
- CSS
- JavaScript
- Canvas API
- Local Storage
- Project files (`.satis`)
- Microsoft Clarity

---

## Definition of Done

A user can:

1. Open SatisStudio
2. Upload an image
3. Add text
4. Move elements around the canvas
5. Save the project as a `.satis` file
6. Open the project later
7. Export the final image as a PNG
