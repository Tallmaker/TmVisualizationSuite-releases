---
title: Good to know
order: 40
---

# Notices and limits

A notice line under the map states when the map shows less than the full result.

- The map loads at most 20,000 rows.
- Above 5,000 areas at the chosen resolution, the map uses a coarser resolution. When no coarser resolution fits, it keeps the 5,000 areas with the largest values.
- A row with a missing or an invalid latitude or longitude is not drawn. A missing weight is not a zero weight.

A state panel replaces the map when the selection has no rows, a required role has no field, or the result is too large to draw.
