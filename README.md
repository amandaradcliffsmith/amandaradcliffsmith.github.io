# amandaradcliffsmith.github.io

Website for **Stop Math Mimicking**, a Radcliff-Smith Consulting offering, live at <https://stopmathmimicking.com>.

It's a [Jekyll](https://jekyllrb.com/) site that GitHub Pages builds and publishes automatically on every push to `main`.

## Layout

- `_config.yml`: site title, description, URL, and plugins
- `_layouts/default.html`: the shared page wrapper
- `index.html`: the home page (currently "coming soon")
- `404.html`: the "page not found" page
- `assets/css/style.css`: site styles
- `CNAME`: the custom domain for GitHub Pages; don't remove it

## Local preview (optional)

Needs Ruby and Bundler:

```bash
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>.
