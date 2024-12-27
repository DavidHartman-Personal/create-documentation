# Calculator Documentation

This site contains the project documentation for the
`calculator` project that is a toy module used in the
Real Python tutorial
[Build Your Python Project Documentation With MkDocs](
    https://realpython.com/python-project-documentation-with-mkdocs/).
Its aim is to give you a framework to build your
project documentation using Python, MkDocs,
mkdocstrings, and the Material for MkDocs theme.

Steps/Notes for this project:

* Needed to add a new venv for just this project as many of the requirements were not in the global site package (e.g. mkdocs).
* After adding new Python interpreter activated the venv in PowerShell by running `venv\Scripts\activate`.
* Ran `python -m mkdocs new .`.  As site folder, etc. already existed, response notes that Project already exists.
* Needed to add calculator\ directory as a "Source" resource for the project structure in PyCharm.
* Then run the mkdocs_serve, which runs `mkdoc serve`.  This starts an http server with the docs/ folder as the root.

## Table Of Contents

The documentation follows the best practice for
project documentation as described by Daniele Procida
in the [Diátaxis documentation framework](https://diataxis.fr/)
and consists of four separate parts:

1. [Tutorials](tutorials.md)
2. [How-To Guides](how-to-guides.md)
3. [Reference](reference.md)
4. [Explanation](explanation.md)

Quickly find what you're looking for depending on
your use case by looking at the different pages.

## Project Overview

::: calculator.__init__

## Acknowledgements

I want to thank my house plants for providing me with
a negligible amount of oxygen each day. Also, I want
to thank the sun for providing more than half of their
nourishment free of charge.
