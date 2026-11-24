# VTEX Architecture Diagram

Interactive VTEX Constellation diagram for Solution Engineering presentations (NRF 2027, US audience).

## Usage

Open `index.html` in a browser (double-click or drag into a tab). No build step required.
Partner logos load from `assets/logos/`, so keep that folder next to `index.html`.

## Features

- Click any core module or tooling box to mark it as discussed during a session
- Toggle **Sales Channel** (B2C, B2B, POS (In-store), PunchOut, Multi-brand, Multi-country) to highlight the relevant VTEX modules
- Click a **paid add-on** for a short description, an **integration** box (Payments, Carriers, Google UCP) for partner logos, or **Sales App** for the demo video. Popups are small liquid-glass bubbles that unfold from the box you clicked; click elsewhere or press Esc to close
- Reset button in the header clears all highlights, channel selections and any open popup

## Notes

- Sales channel colours come from the VTEX brand palette (extended "Rebel Rainbow": Vibrant Green, Marigold Yellow, Sunset Orange, Electric Teal, Cobalt Blue, Bubble Gum Pink). Paid add-ons use a muted plum (#822B6B) with the same wash and border as native pink
- Colour code: pink = native VTEX module, purple = paid add-on, blue = admin and developer tooling, grey = partners and integrations
- Sales App demo video: set `SALES_APP_VIDEO` at the top of the script in `index.html` (until then the popup shows a placeholder)
- Designed as a fixed-proportion slide canvas that scales to fit any viewport
