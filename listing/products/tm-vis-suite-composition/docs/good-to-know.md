---
title: Good to know
order: 40
---

# Notices and limits

The chart prefers a reduced view with a notice to a refusal. Qlik keeps the largest 11 categories and the largest 5 split values and groups the rest as Other. Other has no selection identity.

- 100% stacked proportion, Waffle, and Unit chart draw at most 24 parts. Waffle and Unit chart draw at most 2,500 marks.
- Marimekko / mosaic draws at most 500 cells. Parallel sets draws at most 48 ribbons and needs an object at least 320 pixels wide.
- A share below the format step reads less than 0.1%, never 0%. A measured zero draws as 0%.

A state panel replaces the chart when the selection has no rows, the values are not additive, a Value is negative, or the object is too small.
