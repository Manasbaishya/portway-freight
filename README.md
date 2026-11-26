# Portway Freight – Freight Control Tower (demo)

A single-page prototype of the freight flow:
Ariba PO → supplier shipment details → forwarder RFQ → quote comparison → NFA → Ariba PO → AWB tracking → delivery, plus an Exec Dashboard.

- Runs entirely in the browser: no server, no login, no build step.
- All data is **sample data**, stored only in the viewer's browser (localStorage). "Reset sample data" restores it.
- Switch roles with **Viewing as** (Logistics Center, any supplier, any forwarder).

## Run locally
Double-click `index.html`, or in VS Code use the Live Server extension.

## Publish (GitHub Pages)
Repo → Settings → Pages → Source: *Deploy from a branch* → Branch: `main` / root → Save.
The site appears at `https://<your-username>.github.io/portway-freight/`.

Do not put real PO, supplier or pricing data in a public repository.
