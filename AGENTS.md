# Project Agent Notes

- Keep coding concise with minimal whitespace; prefer short, modular functions and files under 1000 lines when practical.
- Use single-line, high-level comment descriptors for functions, with up to 3 relevant usage examples only when useful.
- Keep related file names grouped with common prefixes when adding feature-specific files.
- Keep `index.html` consistent with the existing single-page portfolio style.
- Project highlight entries use a left title/media column and right descriptive paragraph; new entries should match that pattern.
- Recent update: added `Project A.T.O.M.` and `AI Materials Discovery` above `VLM Tuner`, added the materials project video embed, and fixed the malformed responsive `.column` CSS rule.
- Blog: `/blog/` is a buildless HTML archive with three long-form 2026 essays. Each article has its own `blog/<slug>/index.html`; shared responsive/print styles live in `assets/css/blog.css`. Keep the portfolio change limited to the Blog button below Contact and project anchor IDs used by article links.
- Blog assets: original explanatory SVGs and PNG social previews use the `assets/images/blog/blog_` prefix. Article text, contents navigation, and source lists work without JavaScript; JSON-LD is metadata only.
- When editing articles, synchronize dates, reading times, canonical/social metadata, JSON-LD, archive entries, related links, `blog/feed.xml`, and `sitemap.xml`; see `blog/README.md`. Ground personal claims in the portfolio, label illustrative examples, and keep sources earlier than each chosen article date.
