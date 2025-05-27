# CRS Draw Data

Express Entry draw data for [CRS Calculator Pro](your-calculator-url).

## Files

- `processed-draws.json` - Lightweight draw data (last 6 months, essential fields only)
- `raw-draws.json` - Full IRCC draw data (backup)

## Data Format

```json
{
  "lastUpdated": "2025-05-26",
  "latest": {
    "cec": { "number": 347, "crs": 547, ... },
    "pnp": { "number": 346, "crs": 706, ... }
  },
  "trends": { ... },
  "totalDraws": 12
}
