# kerincardona.github.io

Personal academic website of Kerin Cardona (CIMNE BEE Group, Universitat de Lleida): https://kerincardona.github.io

Built with [Academic Pages](https://github.com/academicpages/academicpages.github.io) (Jekyll 4) and deployed by GitHub Actions (`.github/workflows/jekyll.yml`). In the repository settings, Pages source must be **GitHub Actions**.

## Editing

- Profile and links: `_config.yml` (`author:` block)
- Home page: `_pages/about.md`
- Publications: `_publications/` (`category`: `manuscripts`, `conferences`, `underreview`)
- Talks: `_talks/`
- Code & data: `_pages/code.md`
- Menu: `_data/navigation.yml`

Do not list double-anonymous submissions under review.

## Local build

```bash
docker run --rm -v "$PWD":/srv -w /srv ruby:3.1 bash -c \
  "bundle config set path /tmp/gems && bundle install && bundle exec jekyll build -d /srv/_site"
```

Template: Academic Pages, a fork of Minimal Mistakes (© Michael Rose), MIT License (see `LICENSE`).
