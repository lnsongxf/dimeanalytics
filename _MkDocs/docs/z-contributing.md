# Contributing

This webpage lives on the [`gh-pages`](https://github.com/worldbank/dimeanalytics/tree/gh-pages) branch of the DIME Analytics repo. It is automatically compiled from the Markdown files in the `/_MkDocs/docs/` folder using [`MkDocs`](https://www.mkdocs.org) and the [Material Theme](https://squidfunk.github.io/mkdocs-material/).

To contribute, check out the `gh-pages` branch. Update only the `.md` materials in the `/_MkDocs/` folder. Then, to compile the site, run:

```
cd _MkDocs
mkdocs build
```

Finally, copy the contents of `/_MkDocs/site/` into the root directory and submit a pull request to the `gh-pages` branch.
