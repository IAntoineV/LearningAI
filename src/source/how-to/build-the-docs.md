# How to build the docs

## With poetry ((almost) mandatory for GitHub Pages)

Install poetry

Go to the project root

Run `poetry install`

Go to src folder

Run `make html`

## Without poetry

Modify Makefile: remove `poetry run`

Install Sphinx and build the docs like you would normally.
