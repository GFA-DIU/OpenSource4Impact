# Open Source Checklsit
[![Built with Material for MkDocs](https://img.shields.io/badge/Material_for_MkDocs-526CFE?style=for-the-badge&logo=MaterialForMkDocs&logoColor=white)](https://squidfunk.github.io/mkdocs-material/)

## Getting started
Create a virtual Python environment
```Bash
python -m venv .venv
```

Install mkdocs-material (more info, [here](https://squidfunk.github.io/mkdocs-material/getting-started/))
```Bash
pip install mkdocs-material
```

Run static page at local host
```Bash
mkdocs serve
```

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.