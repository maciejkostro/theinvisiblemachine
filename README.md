# The Invisible Machine — Essay and Reference Repository

This repository is a **static, text-first public repository** for:

- all public essays
- shared reference pages:
  - dictionary
  - bibliography
  - regulations
  - infrastructure / standards / schemes

It is designed for **GitHub Pages**, with Markdown as the storage format and static HTML as the delivery format.

## What is included

- clean Markdown pages for essays and reference pages
- `robots.txt`
- `sitemap.xml`
- `llms.txt`
- `corpus.json` machine-readable index
- a minimal homepage and section indexes
- essay and reference templates for future additions

## Before publishing

Edit `_config.yml`:

- `title`
- `description`
- `url`
- `baseurl`

Use these rules:

- **Project site** (for example `https://username.github.io/repo-name/`)
  - `url: "https://username.github.io"`
  - `baseurl: "/repo-name"`
- **User site** (for example `https://username.github.io/`)
  - `url: "https://username.github.io"`
  - `baseurl: ""`
- **Custom domain** (for example `https://corpus.theinvisiblemachine.eu/`)
  - `url: "https://corpus.theinvisiblemachine.eu"`
  - `baseurl: ""`

## Optional custom domain

If you want a custom domain:

1. rename `CNAME.example` to `CNAME`
2. replace its content with your real domain, for example:
   - `corpus.theinvisiblemachine.eu`
3. configure the matching DNS records
4. in GitHub Pages settings, confirm the custom domain

## GitHub Pages setup

1. Create a **public repository**.
2. Upload all files from this folder.
3. In GitHub: **Settings → Pages**.
4. Set source to:
   - **Deploy from a branch**
   - branch: `main`
   - folder: `/ (root)`
5. Save.
6. Wait for the site URL to appear.

## What to check after publishing

Open these URLs and confirm they load:

- `/`
- `/essays/`
- `/references/`
- `/robots.txt`
- `/sitemap.xml`
- `/llms.txt`
- `/corpus.json`

## How to add a new essay

1. Copy `templates/essay-template.md`
2. Create a new folder under `essays/your-slug/`
3. Save the file as `index.md`
4. Fill in the front matter:
   - `title`
   - `description`
   - `date_published`
   - `order`
   - `canonical_source`
5. Add the essay text below the front matter.

## How to update the reference pages

Each shared reference page lives in:

- `references/dictionary/index.md`
- `references/bibliography/index.md`
- `references/regulations/index.md`
- `references/infrastructure-standards-schemes/index.md`

Edit those files directly.

## Notes on machine readability

This repository intentionally keeps everything simple:

- text-first Markdown
- no JavaScript dependency
- stable URLs
- crawler-facing discovery files

That makes it suitable for both normal human browsing and AI retrieval systems.
