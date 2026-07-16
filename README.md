# Documentation Templates Library

**A curated collection of 58 production-ready HTML and Markdown templates for beautiful, professional documentation.**

Great documentation is a design problem as much as a writing one. This library is a set of drop-in starting points I built while writing READMEs, API references, dashboards, and long-form documents — everything from a GitHub-flavored README to a print-ready magazine layout. Copy a file, swap in your content, and ship.

---

## Why this exists

Most documentation stalls at a blank page. You know *what* you want to say but not how to make it look credible, scannable, and finished. These templates solve the "how it looks" half so you can focus on the words:

- **Markdown templates** render cleanly on GitHub, in Obsidian, and in most static-site generators — no build step, no dependencies.
- **HTML templates** are single-file, self-contained pages (inline CSS, web-font links) that open straight in a browser and print to PDF without a toolchain.
- Everything uses **sample data only** (`example.com`, `555-0100`, placeholder names), so there's nothing to scrub before you reuse it.

---

## What's inside

| Category | Count | Format | Highlights |
| --- | ---: | --- | --- |
| HTML layout templates | 20 | `.html` | Magazines, lookbooks, annual reports, catalogs, portfolios, wedding album |
| Markdown documentation templates | 38 | `.md` | README, API docs, CHANGELOG, CONTRIBUTING, architecture docs |
| README theme variants | 6 | `.md` | Ocean Blue, Sunset Warm, Forest Nature, Monochrome, Enhanced, base |
| Dashboard / CRM templates | 4 | `.md` | Metrics dashboards, colorful CRM boards |
| **Total template files** | **58** | | |

```
documentation-templates/
├── HTML/        # 20 self-contained, print-ready HTML page layouts
└── Markdown/    # 38 Markdown documentation & component templates
```

---

## Gallery

### HTML page layouts (`HTML/`)

Each file is a complete, standalone page — open it in any browser or export to PDF.

| File | Layout | Best for |
| --- | --- | --- |
| [`06_annual_report_corporate.html`](HTML/06_annual_report_corporate.html) | Corporate annual report | Investor updates, yearly summaries |
| [`12_annual_report_creative.html`](HTML/12_annual_report_creative.html) | Creative annual report | Agency / studio year-in-review |
| [`07_magazine_dark.html`](HTML/07_magazine_dark.html) · [`08_magazine_light.html`](HTML/08_magazine_light.html) | Editorial magazine | Long-form articles, thought pieces |
| [`02_lookbook_green.html`](HTML/02_lookbook_green.html) · [`03_lookbook_purple.html`](HTML/03_lookbook_purple.html) · [`04_lookbook_pink.html`](HTML/04_lookbook_pink.html) | Product lookbook | Collections, brand catalogs |
| [`09_newspaper_tabloid.html`](HTML/09_newspaper_tabloid.html) | Newspaper / tabloid | Newsletters, press pages |
| [`10_book_launch.html`](HTML/10_book_launch.html) · [`05_rosa_jane_classic.html`](HTML/05_rosa_jane_classic.html) · [`18_memoir_personal.html`](HTML/18_memoir_personal.html) | Book / eBook | Novel previews, memoirs |
| [`13_cookbook_recipe.html`](HTML/13_cookbook_recipe.html) | Cookbook | Recipe collections |
| [`15_portfolio_creative.html`](HTML/15_portfolio_creative.html) | Portfolio | Designer / creative showcases |
| [`16_newsletter_business.html`](HTML/16_newsletter_business.html) | Business newsletter | Quarterly reports |
| [`17_catalog_product.html`](HTML/17_catalog_product.html) | Product catalog | Ecommerce, home goods |
| [`20_wedding_album.html`](HTML/20_wedding_album.html) | Wedding album | Events, keepsakes |

### Markdown templates (`Markdown/`)

| File | Purpose |
| --- | --- |
| [`README_TEMPLATE.md`](Markdown/README_TEMPLATE.md) + 5 theme variants | Project READMEs with badges, quick-start, and env-var sections |
| [`API_DOCUMENTATION_TEMPLATE.md`](Markdown/API_DOCUMENTATION_TEMPLATE.md) | Endpoint reference with request/response examples in JS, Python, Ruby |
| [`SYSTEM_ARCHITECTURE_DOC_TEMPLATE.md`](Markdown/SYSTEM_ARCHITECTURE_DOC_TEMPLATE.md) | Architecture decision records and system diagrams |
| [`CHANGELOG_TEMPLATE.md`](Markdown/CHANGELOG_TEMPLATE.md) · [`CONTRIBUTING_TEMPLATE.md`](Markdown/CONTRIBUTING_TEMPLATE.md) | Keep-a-Changelog and contributor onboarding |
| [`MERMAID_GALLERY_TEMPLATE.md`](Markdown/MERMAID_GALLERY_TEMPLATE.md) · [`02_Mermaid_Diagrams.md`](Markdown/02_Mermaid_Diagrams.md) | Flowcharts, sequence, Gantt, and class diagrams |
| [`Enhanced_CRM_Dashboard.md`](Markdown/Enhanced_CRM_Dashboard.md) · [`04_Dashboard_Metrics.md`](Markdown/04_Dashboard_Metrics.md) | Metrics dashboards built from styled tables and cards |
| [`HTML_CARDS_LIBRARY.md`](Markdown/HTML_CARDS_LIBRARY.md) · [`ULTIMATE_GRID_MASTERY.md`](Markdown/ULTIMATE_GRID_MASTERY.md) | Reusable card and grid components that render in GitHub Markdown |
| [`03_Obsidian_Callouts.md`](Markdown/03_Obsidian_Callouts.md) | Obsidian callout / admonition patterns |
| [`GITHUB_MARKDOWN_GUIDE.md`](Markdown/GITHUB_MARKDOWN_GUIDE.md) · [`ADVANCED_FORMATTING_TECHNIQUES.md`](Markdown/ADVANCED_FORMATTING_TECHNIQUES.md) | Reference guides to advanced GFM features |
| [`INDEX.md`](Markdown/INDEX.md) | Full index of the Markdown collection |

> Browse [`Markdown/INDEX.md`](Markdown/INDEX.md) for the complete, categorized list.

---

## Features

- **Zero dependencies.** No npm install, no build step. Markdown renders anywhere; HTML files are single-file and self-contained.
- **Copy-paste components.** Cards, grids, callouts, metric tiles, and styled tables you can lift into your own docs.
- **GitHub-native.** The Markdown templates use only formatting that renders on GitHub — inline HTML, tables, task lists, and Mermaid.
- **Print-ready.** HTML layouts are tuned for A4/Letter and export cleanly to PDF from the browser's print dialog.
- **Theming.** README templates ship in six color themes; HTML layouts use CSS custom properties so a palette swap is a few variables.
- **Safe sample data.** Every name, email, and phone number is fictional placeholder data.

---

## Tech Stack

- **Markdown** — GitHub Flavored Markdown (GFM), Obsidian callout syntax, Mermaid.js diagrams
- **HTML5 + CSS3** — semantic markup, CSS custom properties, Flexbox & Grid, inline styles for portability
- **Web fonts** — Google Fonts (Inter and friends) via `<link>`; degrade gracefully to system fonts
- **No JavaScript, no framework, no bundler** — by design

---

## How to use

**Markdown template**

1. Pick a file from `Markdown/` (start with [`README_TEMPLATE.md`](Markdown/README_TEMPLATE.md) or [`API_DOCUMENTATION_TEMPLATE.md`](Markdown/API_DOCUMENTATION_TEMPLATE.md)).
2. Copy it into your project and rename it (e.g. `README.md`).
3. Find-and-replace the placeholders — `[Project Name]`, `example.com`, sample metrics — with your own.
4. Commit. It renders immediately on GitHub or in your docs site.

**HTML template**

1. Pick a file from `HTML/` and open it in a browser to preview.
2. Edit the content inline; adjust the CSS variables in `:root` to rebrand.
3. To produce a PDF, use the browser's **Print → Save as PDF** (layouts are print-tuned).

```bash
# Clone and browse locally
git clone https://github.com/builtbyai/documentation-templates.git
cd documentation-templates

# Open an HTML template (macOS `open`, Linux `xdg-open`, Windows `start`)
open HTML/08_magazine_light.html
```

---

## Screenshots

> Rendered previews of a few HTML layouts. To regenerate: open the file in a browser and capture, or export via **Print → Save as PDF**.

| Magazine (light) | Annual report (corporate) | Product catalog |
| --- | --- | --- |
| _`docs/screenshots/magazine_light.png`_ | _`docs/screenshots/annual_report.png`_ | _`docs/screenshots/catalog.png`_ |

| Lookbook | Portfolio | Wedding album |
| --- | --- | --- |
| _`docs/screenshots/lookbook.png`_ | _`docs/screenshots/portfolio.png`_ | _`docs/screenshots/wedding_album.png`_ |

<!-- Add PNGs under docs/screenshots/ and swap the paths above for images:
     ![Magazine light](docs/screenshots/magazine_light.png) -->

---

## License

Released under the [MIT License](LICENSE). Use the templates freely in personal and commercial projects.
