# r-static-renv

Static R content with an `renv.lock` and no `manifest.json`. Used by
vivid-serving-tests to check that Connect Cloud builds R dependencies from
`renv.lock` alone.

- `report.Rmd` — publish as `rmd-static`
- `report.qmd` — publish as `quarto-static`

Regenerate the lockfile with `renv::snapshot()`. Do not add a `manifest.json`.
