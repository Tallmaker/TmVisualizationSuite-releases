---
title: Getting started
order: 10
---

# Set up an object

Drag **Tm Process Explorer** from **Custom objects** to the sheet. Add the dimensions and measures that the mode needs, up to four of each. In **Data roles**, select a mode in **Chart type**, then map one field for each role.

**Case** is one instance of the process. **Event**, **Stage**, and **Occurrence** name what happens. **Start** and **End** are measures that return a date or a timestamp for each row, for example `Only(EventStart)`. **Weight** sets the size of a transition or a stage. **Order** sets an explicit step order.

For Funnel, select **One total bar** or **One bar per case** in **Bars per stage**.
