# OpenSource4Impact

[![Built with Material for MkDocs](https://img.shields.io/badge/Material_for_MkDocs-526CFE?style=for-the-badge&logo=MaterialForMkDocs&logoColor=white)](https://squidfunk.github.io/mkdocs-material/)


Welcome to the *Open Source guideline for Development Cooperation projects*. This repository contains all the source files behind the guideline. It is designed to help people working in development cooperation to:

  - Take a well-informed decision for or against the use, introduction or development of open source tools 
  - Avoid late failure and unexpected cost through appropiate planning

It is written from the perspective of practitioners working in publicly funded development cooperation projects and organizations. We wish for that it might make a contribution towards more successful open source endeavors and more sustainable digital solutions in general.

## Contributing

This project would like to provide a welcoming place to learn from the various experiences on implementing open source projects within development cooperation. We therefore welcome different **types of contributions**, most of them don't require you to write a single line of code.

If you're looking for a way to contribute, you can scan through our [existing issues](https://github.com/GFA-DIU/GFA-DIU.github.io/issues) for something to work on. 

For more complex contributions, you can [open an issue](https://github.com/GFA-DIU/GFA-DIU.github.io/issues) to describe the changes you'd like to see.


### Join us in discussions

We use GitHub Discussions to talk about all sorts of topics related to documentation and this site. For example: if you'd like help troubleshooting a PR, have a great new idea, or want to share something amazing you've learned in our docs, join us in the [discussions](https://github.com/GFA-DIU/GFA-DIU.github.io/issues).

## License

Any text within in the *docs* folders is  licensed under the [Creative Commons Zero 1.0](https://creativecommons.org/publicdomain/zero/1.0/).

Any code within this repo is licenced under the [MIT](LICENSE-CODE) licence.


## For developers

In the following we provide a short guide on how to get started with the (local) development and installation of this documentation.

### Getting started
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

### Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

### Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
