# Creator Communication Flow Editor

A small, standalone web tool for designing Benable's creator-facing communication timelines. Edit stages and touchpoints (Email, SMS, In-app, IG DM) inline, drag to reorder, share a snapshot via URL.

## Use it

Open `index.html` in any modern browser. State auto-saves to `localStorage`. Use **Copy share link** to send the current flow to a teammate — the state lives entirely in the URL fragment, nothing hits a server.

## Deploy

GitHub Pages from `main`. `.nojekyll` keeps the deploy as-is.

## File layout

Single `index.html`. No build step, no dependencies.
