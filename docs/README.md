# PreBook Docs

These docs require [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/).

To set it up, clone this repo, install [pipenv](https://pipenv.pypa.io/en/latest/index.html#install-pipenv-today), `cd` to this folder, and do the following:

```
pipenv install
```

Then, to serve the site locally with live reloads, run:

```
pipenv run serve
```

To build the site, run:

```
pipenv run publish
```
The site will be in `<repo root>/docs/public`.
