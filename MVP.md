# SatisStudio MVP

## Goal

Create a simple, open-source online image editor focused on creating stickers, banners, and graphics.

The MVP should be lightweight, browser-based, and require no backend or database.

---

## Core Features

### Canvas

-[x] Canvas for placing and editing elements
-[x] Fixed-size canvas

### Images

- [x] Upload images
- [x] Render images on the canvas
- [x] Move images around the canvas

### Text

-[x] Add text elements
-[x] Edit text
-[x] Move text around the canvas

### Projects

- [x] Save projects to a `.satis` file
- [x] Open existing `.satis` files
- [x] Import projects from disk
- [x] Export projects to disk

Project files are versioned JSON documents containing the canvas dimensions,
embedded PNG image assets, and editable text/image elements. Element positions
and sizes are measured in canvas pixels from the top-left corner; rotations are
stored in radians.

Saving prompts for a project name and downloads `<name>.satis`. Opening a project
uses its filename as the project name. PNG export downloads `<name>_Output.png`
with the canvas content and without editor selection controls.

### Export

- [x] Export canvas as PNG

---

## Analytics

Use Microsoft Clarity to understand how the editor is used, only after analytics consent.

Track events:

- [x] import-image
- [x] add-text
- [x] save-project
- [x] open-project
- [x] export-png

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
5. Name and save the project as a `.satis` file
6. Open the project later
7. Export the final image as a PNG
