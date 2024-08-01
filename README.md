# Classes

Bridger's class pages.

## Introduction
This is based on the MkDocs template [![Built with Material for MkDocs](https://img.shields.io/badge/Material_for_MkDocs-526CFE?style=for-the-badge&logo=MaterialForMkDocs&logoColor=white)](https://squidfunk.github.io/mkdocs-material/) and the [Obsidian Publish MkDocs](https://github.com/jobindjohn/obsidian-publish-mkdocs) template.


I use Obsidian notes to create the pages in Markdown, then I use MkDocs (Python) to preview:

```bash
python3 -m mkdocs serve
```

and finally to publish:

```bash
python3 -m mkdocs gh-deploy
```



## Adding a new class

1. Create the class folder structure in the `docs` folder
2. In `mkdocs.yml`, add the class to the `extra_titles` dictionary
	- this maps the folder structure to display the appropriate title for whichever class's content is currently being viewed

> [!NOTE]
> Usage of the `extra_titles` dictionary causes a warning when MkDocs is run (since this is a custom key not used by MkDocs). It may be safely ignored.