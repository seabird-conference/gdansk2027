# Seabird Conference 2027

Website for the Seabird Group Conference, 6–10 September 2027, Gdańsk, Poland.

Live site: https://seabird-conference.github.io/

Built with [Hugo](https://gohugo.io/) (extended, v0.165.0) and the [Blowfish](https://blowfish.page/) theme. No CMS, no database — just Markdown files, auto-deployed via GitHub Actions on every push to `main`.

## Setup

```bash
brew install git hugo   # macOS
git clone https://github.com/seabird-conference/seabird-conference.github.io.git
cd seabird-conference.github.io
```

## Preview locally

```bash
hugo server
```

Open http://localhost:1313 — the page reloads automatically as you save changes.

## Where things live

- `content/` — page text (Markdown)
- `data/slideshow.yaml` — homepage image carousel
- `assets/images/` — logos, backgrounds, slideshow photos
- `static/images/` — other page images
- `config/_default/` — site title, menu, theme options
- `layouts/` — custom header/footer overrides
