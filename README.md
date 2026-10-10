# Saurabh S. · Product Portfolio

Source for [saurabhs-pm.github.io](https://saurabhs-pm.github.io/), my product portfolio. I'm a product leader with 12+ years in consumer e-commerce, fintech, payments and customer growth. I build AI and ML products across commerce and payments.

## Selected work

| Project | Area | Status | Write-up |
|---|---|---|---|
| NexRead | AI recommendations | Live | [Case study](https://saurabhs-pm.github.io/case-studies/nexread.html) |
| PaymentIntelligenceOS | Payments | Completed | [Case study](https://saurabhs-pm.github.io/case-studies/paymentintelligenceos.html) |
| Competitive Intelligence RAG | RAG | Completed | [Case study](https://saurabhs-pm.github.io/case-studies/competitive-intel-rag.html) · [Code](https://github.com/SaurabhS-pm/competitive-intel-rag) |
| Cross-border payments | Payments | Completed | On the homepage |
| Voice AI support agent | Voice AI | In progress | On the homepage |

## Skills and tools

RAG, LLMs, agentic AI, Python, Claude APIs, A/B experimentation, consumer payments, card networks, subscription platforms and 0 to 1 products.

## How each case study is written

Every case study follows the same five sections, so they are quick to compare.

| Section | What it covers |
|---|---|
| Problem | Who has the problem and why it matters |
| Approach | What I built and the scope I chose |
| Key decisions | The trade-offs and why I made each call |
| What I found | Results and what the data showed |
| What I would do differently | Lessons and next steps |

## How the site is built

Hand-written HTML and CSS, no frameworks and no build step. GitHub Pages serves the `main` branch as is.

| Path | What it holds |
|---|---|
| `index.html` | Homepage |
| `case-studies/` | One page per case study |
| `assets/case-studies/` | Screenshots used in the case studies |
| `404.html` | Not-found page |
| `sitemap.xml`, `robots.txt` | Search engine indexing |

To preview locally, open `index.html` in a browser, or run `python -m http.server` in this folder and visit `localhost:8000`. Use the local server when checking the 404 page and the favicon, since both use root paths.

To add a case study, copy one of the pages in `case-studies/`, keep the five sections, put screenshots in `assets/case-studies/`, then add the page to the Selected work list in `index.html` and to `sitemap.xml`.

## Design notes

One typeface (Archivo, from Google Fonts), a warm off-white background and a single red accent. Colors live as CSS variables at the top of each page, so a color change is a one-line edit per page. Pages are built to read well at phone width with no horizontal scroll.

## Accessibility

Every screenshot has alt text that describes what it shows, not just its title. Links and buttons have a visible focus outline for keyboard users, and text colors meet contrast guidelines on the off-white background.

## Related repositories

| Repository | What it is |
|---|---|
| [competitive-intel-rag](https://github.com/SaurabhS-pm/competitive-intel-rag) | Code for the Competitive Intelligence RAG case study |
| [SaurabhS-pm](https://github.com/SaurabhS-pm/SaurabhS-pm) | My GitHub profile page |

## Contact

[LinkedIn](https://www.linkedin.com/in/saurabhsrivast/) · [Email](mailto:writeto.saurabhs@gmail.com)
