# Resource Sharing & Lost Found Hub

A static multi-page web project for a campus-style **resource sharing** and **lost & found** experience.

## Overview

This project provides a UI prototype for sharing community resources and managing lost-and-found items.

Key pages include:
- `welcome.html` / `index.html` — landing and introduction
- `login.html` — user sign-in form
- `signup.html` — user registration form
- `dashboard.html` — resource hub with quick category access
- `upload-resource.html` — shared resource submission form
- `lost-found.html` — lost and found item listings
- `report-item.html` — submit a lost or found item report
- `study-materials.html`, `tools-equipment.html`, `books-notes.html` — resource category pages
- `claim-item.html` — claiming found items
- `contact-owner.html` — contacting item/resource owners

The site is frontend-only:
- No JavaScript logic is implemented
- No backend or database persistence exists
- Forms use HTML `action` navigation and do not save data

## Tech Stack

- HTML5
- CSS3
- Static image assets (`assets/`)

## Project Structure

```text
.
|-- index.html
|-- welcome.html
|-- login.html
|-- signup.html
|-- dashboard.html
|-- upload-resource.html
|-- lost-found.html
|-- report-item.html
|-- study-materials.html
|-- tools-equipment.html
|-- books-notes.html
|-- claim-item.html
|-- contact-owner.html
|-- css/
|   |-- _shared-layout.css
|   |-- main-header.css
|   |-- welcome.css
|   |-- login.css
|   |-- signup.css
|   |-- dashboard.css
|   |-- upload-resource.css
|   |-- lost-found.css
|   |-- report-item.css
|   |-- study-materials.css
|   |-- tools-equipment.css
|   |-- books-notes.css
|   |-- claim-item.css
|   |-- contact-owner.css
|-- assets/
|   |-- background.png
|   |-- key.png
|   |-- loupe.png
|   |-- menu-img.png
|   |-- people.png
|   |-- shopping-cart.png
|
```

## Page Flow

1. Open `welcome.html` or `index.html`
2. Go to `login.html` or `signup.html`
3. After sign-in, access `dashboard.html`
4. From the dashboard, navigate to:
   - `study-materials.html`
   - `tools-equipment.html`
   - `books-notes.html`
   - `upload-resource.html`
   - `lost-found.html`
5. In Lost & Found:
   - `report-item.html`
   - `claim-item.html`
   - `contact-owner.html`

## Notes

- `welcome.html` is present in the root and is used by auth/logout links.
- This is a static prototype; no backend authentication or item persistence is available.

## Running Locally

Open `welcome.html` or `index.html` in a browser.

For a local server, use a simple static server, for example:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

