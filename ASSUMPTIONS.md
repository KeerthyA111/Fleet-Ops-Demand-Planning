# Assumptions & Data Decisions

## Scope
- Data source: Kaggle Logistics Operations Database (synthetic, 2022–2024).
  Findings demonstrate method, not real business conclusions.
- Leasing data from a Salesforce Developer Edition org, manually populated.
  Joined to ops data on Region only — no shared key exists.

## Definitions
- Planned volume treated as demand forecast, not capacity commitment.
  Variance is read as forecast error.
- On-time % = SUM(on-time) / SUM(total), not AVERAGE of per-row rates.

## Data handling
_(entries added during profiling — each documents what was done, 
how many rows affected, and why)_
