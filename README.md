A boilerplate [vale](https://vale.sh/docs/) for use locally. https://passo.uno/posts/first-steps-with-the-vale-prose-linter/ provides a better quickstart.


## Commands

Grab the to-date version of a style package referenced in the vale.ini with

`vale sync`

> Microsoft is sourced from https://github.com/errata-ai/Microsoft

To run vale against all relevant files in repo

`vale .`

Or pass vale the path to the file you want to lint, e.g. lint this file with:

`vale README.md`

## Test Headings

This heading should break MS style.

