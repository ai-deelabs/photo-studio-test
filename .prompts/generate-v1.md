Build a landing page as a single file `v1.html` — all CSS
and JS inline, no frameworks.

Brand:
Photo Studio BKK is a photography studio in Bangkok specializing in portrait and commercial photography. The aesthetic is strictly black and white — monochrome throughout, high contrast, dramatic lighting feel. Clean, gallery-like presentation with generous whitespace. The studio targets creative professionals and brands looking for striking visual content.

This is variant 1 of 2.
Express the brand's style through layout, whitespace, typography,
visual rhythm, and photo treatment — not just color. Avoid cliché
color associations (gold for luxury, blue for trust, green for health).

Responsive, mobile-first. Set `<html lang="en">`.
Logo is text-only (styled with CSS/fonts) — no image logos.

No emojis. Use Lucide Icons:
`<script src="https://unpkg.com/lucide@0.460.0"></script>` in head,
`<i data-lucide="icon-name"></i>` in body, `lucide.createIcons()` at end.

Images — search with different keywords per section:
`bash /home/runner/work/web-builder-control/web-builder-control/core/tools/search-images.sh "keyword" [count]`
Use returned URLs in `<img>` with `?w=WIDTH&h=HEIGHT&fit=crop`.
Fallback: `https://picsum.photos/seed/{keyword}/{width}/{height}`.

No X-Frame-Options (this page loads inside an iframe for preview).
