# amandaradcliffsmith.github.io

Website for **Stop Math Mimicking**, a Radcliff-Smith Consulting offering, live at <https://stopmathmimicking.com>.

It's a [Jekyll](https://jekyllrb.com/) site that GitHub Pages builds and publishes automatically on every push to `main`.

## Everyday edits

| To change… | Edit |
|---|---|
| Contact email, LinkedIn/YouTube links, founder photo | `_config.yml` (see the comments there) |
| AWeber sign-up form (list, form ID, redirects) | `signup:` section of `_config.yml` |
| Page new subscribers see after signing up | `thanks.html` |
| Teacher testimonials (section appears once the list has entries) | `_data/testimonials.yml` |
| Talks and press (section on About appears once the list has entries) | `_data/talks.yml` |
| Menu links | `_data/navigation.yml` |
| Add an article | New file in `_posts/` named `YYYY-MM-DD-title.md` (copy the existing one) |

## Layout

- `_layouts/`: `default` (header and footer), `page` (plum page hero), and `post` (articles)
- `_includes/`: header, footer, wordmark, margin note, sign-up block, and testimonials
- Pages: `index.html`, `about.html`, `workshops.html`, `resources.html`, `contact.html`, and `404.html`
- `assets/css/style.css`: all styles, with brand colors and fonts as CSS variables at the top
- `CNAME`: the custom domain for GitHub Pages; don't remove it

## Local preview (optional)

Needs Ruby and Bundler:

```bash
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>.
