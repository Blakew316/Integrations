# Integration Atlas

An interactive, filterable directory of every POS system, business platform, and payment
gateway in the *Integration List* workbook — 735 unique systems, each enriched with:

- **Category** — one of 20 buckets (Restaurant & Bar POS, Retail POS, Veterinary & Pet, …)
- **Rank** — a 1–10 read on the software's overall strength today (10 = best)
- **SaaS fees** — the vendor's published pricing, web-verified for major vendors
- **3 benefits** — why merchants pick it
- **Processing compatibility** — the workbook's integration status (integrated before /
  likely / maybe / unlikely / won't allow), supported front-end platforms
  (Omaha, Rapid Connect, Nashville, North, Buypass, TSYS), and gateway notes

## Using it

Open `index.html` in any browser — it's fully self-contained (no build step, no server,
no external requests). Search with `/`, filter by category pills, status, or platform,
and click any card for the full breakdown.

## Files

| Path | What it is |
| --- | --- |
| `index.html` | The site — single file, data embedded |
| `data/integrations.json` | The enriched dataset, for reuse |
| `data/Integration List.xlsx` | The source workbook |

## Data provenance

Statuses mirror the source sheet (a find/replace accident in the sheet that turned "no"
into "will not allow" has been reversed during import). Rankings and fees are directional
estimates as of Aug 2026, web-verified where the vendor publishes pricing. Always confirm
pricing and compatibility with the vendor before quoting a merchant.
