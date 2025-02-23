---
title: Documentation
---

We are using [MkDocs](https://www.mkdocs.org/) with the [Material for MkDocs theme](https://squidfunk.github.io/mkdocs-material/).

## Markdown Extensions

Thanks to the MkDocs Material theme we have certain "markdown syntax extensions" available:

* [Admonitions](https://squidfunk.github.io/mkdocs-material/reference/admonitions/)
* [Footnotes](https://squidfunk.github.io/mkdocs-material/reference/footnotes/)
* [Icons, Emojis](https://squidfunk.github.io/mkdocs-material/reference/icons-emojis/)
* [Task lists](https://squidfunk.github.io/mkdocs-material/reference/lists/#using-definition-lists)
* And [more](https://squidfunk.github.io/mkdocs-material/reference/)..

For a whole list of features [Reference - Material for MkDocs](https://squidfunk.github.io/mkdocs-material/reference/).

## Local Preview

To locally preview the documentation, you can run the following command (in the root of the repository):

```console
make docs-preview
```

When previewing, now you can navigate your browser to [http://127.0.0.1:8000/](http://127.0.0.1:8000/) to open the preview of the documentation.

!!! hint
    Should you encounter a `command not found` error while trying to preview the docs for the first time on a machine, you probably need to install the dependencies for MkDocs and extensions used.

    ```console
    pip3 install -r build/release/requirements_docs.txt
    ```

    Please make sure that your Python binary path is included in your `PATH`.
