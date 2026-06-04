# Achieveng BD Intelligence Portal

Internal business development intelligence portal covering California public agency capital programs.

## Structure

```
index.html          ← Main portal (agency cards, pipeline tracker)
registry.json       ← Single source of truth for all agency metadata
tools/
  santa_clara.html  ← City of Santa Clara — Measure I Bond
  fresno_county.html← County of Fresno — FY 2025-26 CIP
  modesto.html      ← City of Modesto — FY 2025-26 CIP
```

## Adding a New Agency

1. Build the agency HTML intelligence tool
2. Drop it in `tools/[agency_id].html`
3. Add an entry to `registry.json`
4. Push — portal updates automatically

## Viewing

Open `index.html` in any browser, or visit the GitHub Pages URL once enabled.

**Internal use only. Not for distribution.**
