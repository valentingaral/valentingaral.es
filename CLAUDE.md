# valentingaral.es

Static personal site of Valentin Garcia Alcocer, published with GitHub Pages (custom domain in `CNAME`).

- `index.html` home, `contact.html` contact, `design.html` design archive, `es/` Spanish versions, `assets/` images.
- Style: black #0A0A0A background, white text, accent green #D4FF00. Fonts: Archivo (headlines, wide 125%) and JetBrains Mono (labels).
- English is the default; Spanish (Spain) versions live in `es/` (index, contact, design) with an EN / ES switch in the header and hreflang links. Keep both languages in sync. Avoid dashes in copy; prefer parentheses.
- Logos in the "Worked with" and "Seen & heard" carousels are white PNG/SVG silhouettes; each carousel lists its logos twice in a row so the CSS loop is seamless (keep both copies in sync).
- Plain HTML with inline styles, no build step: edit and commit to `main`, Pages redeploys automatically.
