# AGENTS.md

## Project goal
Build the weekly ranking system for Bonela Bike & Trail from manually pasted Strava club activity data.

## Core principles
- Preserve historical data as the source of truth.
- Never silently guess ambiguous activity classifications; use REVIEW.
- Detect duplicates before adding activities to the historical dataset.
- Validate parser and classifier before finalising scoring rules.
- Keep real member/activity data out of public repositories.
