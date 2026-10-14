# Blog maintenance

The blog is plain HTML served by the existing GitHub Pages site at `https://www.schuback.tech/blog/`. No package installation, build step, database, or client-side rendering is required.

- `index.html` lists articles newest first; each article lives in its own descriptive folder with an `index.html`, producing `/blog/article-slug/` URLs.
- `../assets/css/blog.css` contains the shared responsive layout and print styles. Keep portfolio styles separate.
- `../assets/images/blog/blog_*.svg` are original explanatory diagrams. Archive previews deliberately mix the safety diagram, a portfolio robot photograph, the VLM Tuner screenshot, and a conceptual AI-generated cover for the control essay. Social metadata follows each preview. The new cover's asset path, provenance, and full generation prompt are recorded in `blog_image-notes.md`.
- `feed.xml` is an RSS 2.0 feed with article summaries. `../sitemap.xml` lists the portfolio and blog pages.

To add an article, copy an existing article folder, edit its body, title, description, date, reading time, canonical URL, social metadata, JSON-LD, and contents links. Update the archive, related-article links, RSS feed, and sitemap. Article text is present directly in the HTML and remains readable with JavaScript disabled. The author-selected dates are December 16, 2025 and February 12, June 18, and September 15, 2026; sources predate each article's date. Worked examples describe proposed approaches, not measured project results. The December essay treats autonomous-agent control and civic accountability broadly, separating observed capabilities and laboratory findings from hypothetical future risks.

Preview by opening the repository's `index.html` directly in a browser and clicking Blog, or by opening `blog/index.html`. All navigation and asset references use document-relative paths with explicit `index.html` filenames so `file://` navigation works across the archive, articles, and portfolio. Preserve this convention when adding links; root-relative paths such as `/blog/` resolve to the drive root in a local file preview. Canonical/social metadata, JSON-LD, RSS entries, and sitemap URLs remain absolute HTTPS URLs for the published site.

For an HTTP preview, run `python -m http.server 4173` from the repository root and open `http://localhost:4173/blog/`. Check narrow and wide layouts, article contents anchors, local links, and images. Publication uses this repository's existing GitHub Pages source; a push to the configured publishing branch triggers its normal deployment. The blog needs no hosting or DNS changes.
