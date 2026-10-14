# Blog maintenance

The blog is plain HTML served by the existing GitHub Pages site at `https://www.schuback.tech/blog/`. No package installation, build step, database, or client-side rendering is required.

- `index.html` lists articles newest first; each article lives in its own descriptive folder with an `index.html`, producing `/blog/article-slug/` URLs.
- `../assets/css/blog.css` contains the shared responsive layout and print styles. Keep portfolio styles separate.
- `../assets/images/blog/blog_*.svg` are original explanatory diagrams; their PNG versions provide social sharing images. The existing Empirical Automation portfolio image is reused with a contextual caption.
- `feed.xml` is an RSS 2.0 feed with article summaries. `../sitemap.xml` lists the portfolio and blog pages.

To add an article, copy an existing article folder, edit its body, title, description, date, reading time, canonical URL, social metadata, JSON-LD, and contents links. Update the archive, related-article links, RSS feed, and sitemap. Article text is present directly in the HTML and remains readable with JavaScript disabled. The author-selected dates for the initial essays are February 12, June 18, and September 15, 2026; their sources predate the respective dates. Worked examples describe proposed approaches, not measured project results.

Preview from the repository root with `python -m http.server 4173`, then open `http://localhost:4173/blog/`. Check narrow and wide layouts, article contents anchors, local links, and images. Publication uses this repository's existing GitHub Pages source; a push to the configured publishing branch triggers its normal deployment. The blog needs no hosting or DNS changes.
