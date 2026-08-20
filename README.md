# Prime Time Sellers — Quiz Funnel

Static, self-contained HTML. No build step, no dependencies, no folder structure to preserve —
every file inlines its own fonts, images and styles, so each one works opened directly from disk.

| File | Page |
| --- | --- |
| `index.html` | Landing page (Are You Ready for Prime Time?) |
| `2-quiz-page.html` | Email gate + 10-question assessment |
| `3-results-page.html` | Score, tier, 9-pillar readout |
| `4-audit-sales-page.html` | Healthcare Commercialization Audit™ sales page |
| `prime-time-funnel-all-pages.html` | All four screens in one file, with a preview switcher |

## Publishing with GitHub Pages

1. Create a new repository and upload these files to the root.
2. Settings → Pages → Source: **Deploy from a branch**, branch `main`, folder `/ (root)`.
3. The site appears at `https://<user>.github.io/<repo>/`.

## Notes

- Purchase buttons currently scroll to the pricing block. Point them at the real checkout URL.
- The three testimonial cards on the sales page are labelled placeholders awaiting approved quotes.
- The audit price is set in one place in the source.
