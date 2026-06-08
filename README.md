# action-brew-install

A GitHub action for quickly installing one or more Homebrew formulas

## Example

```yml
-
  name: Install tools
  uses: slingshot-pipelines/action-brew-install@v0
  with:
    FORMULAS: |
      actionlint
      tj-actions/tap/auto-doc
```

## Inputs

<!-- AUTO-DOC-INPUT:START - Do not remove or modify this section -->

|  INPUT   |  TYPE  | REQUIRED | DEFAULT |                   DESCRIPTION                   |
|----------|--------|----------|---------|-------------------------------------------------|
| FORMULAS | string |   true   |         | A newline-delimited list of formulas to install |

<!-- AUTO-DOC-INPUT:END -->

## Outputs

<!-- AUTO-DOC-OUTPUT:START - Do not remove or modify this section -->
No outputs.
<!-- AUTO-DOC-OUTPUT:END -->
