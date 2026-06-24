# Developing

This is a [Jekyll](https://jekyllrb.com/) site served via GitHub Pages at [chignell.nz](https://chignell.nz).

## Prerequisites

- Ruby 3.3.4 (see `.ruby-version`; use [rbenv](https://github.com/rbenv/rbenv) or similar)
- Bundler: `gem install bundler`

## Setup

```sh
bundle install
```

Gems install to `vendor/bundle` (per `.bundle/config`).

## Run locally

```sh
bundle exec jekyll serve
```

Site builds to `_site/` and is served at <http://localhost:4000>. Add `--livereload` to auto-refresh on changes.
