## New

- A demo app is available as a separate download: a project management schedule on seven sheets.
- Each release lists its checksums in a `release-manifest.json`.

## Changed

- The License tab, window, and watermark show the Aderian Tallmaker logo and the name “Tm Gantt”. The author is Tallmaker AS, and product links open the Tm Gantt page.
- Licenses are checked offline by the shared Tallmaker package. While a license needs attention, a strip at the chart foot holds the License tab, so it covers no rows, bars, or controls. A licensed chart looks the same.

## Fixed

- A valid license no longer shows the License tab when the Tm Licensing carrier text ends with a newline.
- Selections, scrolling, Overflow Activities, time axis, schedule dates, colors, tooltips, and keyboard behavior were repaired. Out-of-range dates no longer hide bars, and saved colors and theme fonts can no longer inject CSS.

## Before you upgrade

- A license with several problems can show a different reason than before.
- While a license needs attention, the strip leaves fewer rows visible; scroll to see the rest.
- Licensing still uses the separate Tm Licensing carrier extension. Reload Qlik after installing or replacing it.
