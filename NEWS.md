
## Sverto 1.0.0

- Significant refactor of Sverto makes it easier to use and more compatible with Quarto's other features
- Use Sverto in a Quarto document by adding `sverto` to `filters` in the document frontmatter
- Add Svelte files to a document using the frontmatter key `sverto.use`
- No need for magic blocks anymore!
- When working in a website project, optionally use the `sverto` project type to cut down on duplicate Svelte compilation Quarto documents
- Works properly with Quarto includes
- Requires Quarto pre-release 1.5.25 or higher on Windows, but should work fine on Quarto 1.4 on macOS and Linux.

## Sverto 0.0.3

- Migrated from [`360-info/sverto`](https://github.comn/360-info/sverto) to [`jimjam-slam/sverto`](htps://github.com/jimjam-slam/sverto). Old GitHub links are maintained.

## Sverto 0.0.2

- Bump minimum Quarto version to 1.3.0.
- Fixes for compatibility with newer Quarto 1.3 pre-releases
  - Quarto's switch from Pandoc 2 to Pandoc 3 caused some issues with the way Sverto identifies Svelte import statements. This should no longer be a problem.
- We now take advantage of the improved `.quartoignore` functionality in Quarto 1.3 to:
  1. avoid copying the `docs` folder in with the project template; and
  2. include the `.gitignore` with the template

## Sverto 0.0.1

- Initial release
