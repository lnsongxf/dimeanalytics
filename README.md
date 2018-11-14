# There's nothing here!

This is the backend for the [DIME Analytics website](https://worldbank.github.io/dimeanalytics/). As you can see, it's on GitHub, so you can fork and make suggestions to the webpage content in the `gh-pages` branch. Feel free!

This webpage lives on the `gh-pages` branch of the DIME Analytics repo. It is automatically compiled from the Markdown files in the `/_MkDocs/docs/` folder using [`MkDocs`](https://www.mkdocs.org) and the [Material Theme](https://github.com/squidfunk/mkdocs-material).

To contribute, check out the `gh-pages` branch. Update only the .md materials in the `/_MkDocs/` folder. Then, to compile the site, run:

```
cd _MkDocs
mkdocs build
```

Finally, delete eveything in the root directory except `/_MkDocs/`; copy the contents of `/_MkDocs/site/` into the root directory; and submit a pull request to the `gh-pages` branch.
