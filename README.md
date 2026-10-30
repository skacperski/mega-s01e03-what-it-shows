# MEGA S01E03: what it shows

This repository contains the support desk's KB export and the follow-up to ticket #4471. The export has 412 unique reports, grouped into a shared parser problem and a booking-v3 date-hint problem.

- [Parser issue](https://github.com/skacperski/mega-s01e03-what-it-shows/issues/1): 379 reports.
- [Booking-v3 hint issue](https://github.com/skacperski/mega-s01e03-what-it-shows/issues/2): 33 reports.
- [KB source](support-kb/src/routes/kb/incidents/4471-causes/+page.svx)
- [Rendered KB page](support-kb/src/routes/kb/incidents/4471-causes/rendered.html), a snapshot generated from the supplied Svelte components and export data.
- [KB export conventions](support-kb/README.md)

The export's data is a snapshot. The source page derives its counts from the data and identifies the desk's one-day-move notes for follow-up.
