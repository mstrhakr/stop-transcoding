# Stop Transcoding Docs

This repository contains a simple Jekyll-based documentation site for Plex end users.

## Setup

1. Enable GitHub Pages and set the source to the `docs/` folder.
2. Keep Jekyll enabled; this site uses the `minima` theme.
3. Add or update client guides in `docs/`.

## Local preview

Install Ruby and Jekyll, then run:

```bash
gem install bundler jekyll
bundle exec jekyll serve --source docs --watch
```

Then open `http://127.0.0.1:4000`.

## Content

The site currently includes guides for:

- Xbox One
- NVIDIA Shield
- Android TV
- Roku
- Fire TV
- Apple TV
