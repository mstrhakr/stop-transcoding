# Please Stop Transcoding

This repository contains a Jekyll-based help site that shows Plex end users how to set client defaults for maximum quality and direct play.

## Setup

1. Enable GitHub Pages and set the source to the `docs/` folder.
2. Keep Jekyll enabled; this site uses the `minima` theme.
3. Add or update client guides in `docs/`.

## Local preview

Install Ruby and Jekyll, then run:

```bash
gem install bundler jekyll
bundle exec jekyll serve --source docs --config docs/_config.yml --watch
```

Then open `http://127.0.0.1:4000`.

## Screenshots

Add Plex screenshots under `docs/assets/images/` and use the `docs/assets/images/README.md` file for filename guidance.

## Content

The site currently includes guides for:

- Plex Web
- Xbox One
- NVIDIA Shield
- Android TV
- Roku
- Fire TV
- Apple TV
