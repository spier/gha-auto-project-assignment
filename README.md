# gha-auto-project-assignment

Test to automatically move a newly created issue to a given project board, using GitHub Actions.

## Possible Improvements

- remove the label after the issue has been assigned (or rather not?)
- write a catch-all GHA express, so that the target project can be determined from a given label automatically. Would make it easier for people that don't know how to write GHA expressions. See [auto-assign-to-projects.yml](.github/workflows/auto-assign-to-projects.yml)

## Gotchas

Mind [this extra info](https://github.com/marketplace/actions/assign-to-one-project#organisation-or-user-project) when trying to use this with Organisation Projects or User Projects (rather that Repository Projects).

## Some Tech

Uses this GHA:
- https://github.com/marketplace/actions/assign-to-one-project

Alternatives that I did not try:
- https://github.com/marketplace/actions/github-project-automation (see also [further docs](https://docs.github.com/en/actions/guides/moving-assigned-issues-on-project-boards))
