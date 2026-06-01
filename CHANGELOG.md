# Changelog

## 1.0.0 — 2026-06-01

First public release of the **Engineering Ledger** theme for Redmine 6.

- Dark editorial header/menu, warm paper canvas, white content cards
- IBM Plex Sans + Mono typography; monospace tabular data columns
- Petrol/rust accent system with tuned status, priority and flash palettes
- Themed forms, buttons, tables, journals, sidebar, login and query Options panel
- Responsive-aware (no desktop overrides leaking into Redmine's mobile layout)

### Alignment & contrast pass
- Form rows: label line-box matched to the taller themed controls so labels and
  fields share a midline
- Submit rows: buttons and adjacent "Cancel" links aligned on a shared middle
- Top account bar: increased spacing between links
- Login button: normalised line box so the label sits dead-centre
- Selected (context-menu) rows: locked to the petrol accent with white text on
  hover, fixing a white-on-light contrast bug inherited from the row-hover rule
