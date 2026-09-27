# Data

[Back to the list](../README.md)

| File | What it holds |
| --- | --- |
| `funding_opportunities.csv` | One row per opportunity. Opens in Excel or Google Sheets. |
| `funding_opportunities.json` | `items` (all opportunities, with sources), `context` (not direct routes) and `tools` (search tools). |

## Fields

| Field | Meaning |
| --- | --- |
| `category` | Type of funder, from national to global. |
| `name`, `funder`, `home` | The scheme, the organisation, and its country (for national and foreign-government funders). |
| `status` | One of: Open now, Rolling, Next cycle expected, Check status, Invitation / network, Paused. |
| `status_note` | The status in words, as found on the funder's page. |
| `next_date` | A key date before December 2026, in `YYYY-MM-DD`. |
| `fit` | High, Medium or Low fit for clinician-researchers with small projects. |
| `ai` | `yes` if the opportunity is about AI or data. |
| `amount`, `duration` | As stated by the funder. Empty or "not stated" if not confirmed. |
| `countries` | Which of the ten countries are eligible. |
| `eligibility`, `deadline`, `how`, `url` | Who can apply, the deadline in words, how to apply, and the official page. |

All data is CC0: use it for anything, with no need to ask.
