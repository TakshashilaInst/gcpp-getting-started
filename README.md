# GCPP Getting Started

A single-page guide for students on the Takshashila Institution's Graduate
Certificate in Public Policy: programme structure, week-by-week timeline,
key dates, assessment and grading, platforms, academic integrity and FAQs.

Content switches by specialisation — Advanced Public Policy (APP),
Technology and Policy (TP), and Defence and Foreign Affairs (DFA).

Not to be confused with the GCPP Student Handbook, which is a separate and
longer reference document.

## Files

- `index.html` — the whole site. Self-contained: all CSS and JavaScript are
  inline. The only external request is to Google Fonts (Inter, Roboto Mono).
- `.nojekyll` — tells GitHub Pages to serve the file as-is rather than
  running it through Jekyll. Not needed if deploying via Vercel.

## Editing

Open `index.html` in any text editor. To change which content appears under
which specialisation, edit the `data-track` attribute on the relevant
element: `data-track="app tp"` shows a block on those two tabs only.

Dates are cohort-specific and live in one place — the section headed
"Important Dates to Note".

Built to the Takshashila design language.
