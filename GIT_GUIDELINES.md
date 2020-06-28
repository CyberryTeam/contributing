# Git Guidelines

## Table of Contents

- [Branch](#branch)
  - [master](#master)
  - [develop](#develop)
  - [bug/](#bug)
  - [feature/](#feature)
- [Commit](#commit)

## Branch

We have adopted rules on the use and nomenclature of branches. These rules are based on the [Gitflow](https://nvie.com/posts/a-successful-git-branching-model) and [GitHub flow](https://guides.github.com/introduction/flow) workflows.

### master

This is the main branch of the project containing the most stable version.
This branch is subject to restrictions.

### develop

This is the secondary branch of the project containing the version under development.
This branch is subject to restrictions.

### bug/

These branches correspond to the correction of a bug.

They are created from and merge in:
- `master` if it's a critical bug
- `develop` if it's a casual bug

### feature/

These branches correspond to the development of a feature.

They are created from and merge in `develop`.

## Commit

We have adopted the [Conventional Commit](https://www.conventionalcommits.org/en/v1.0.0/) as our commit message standard. It helps maintain a clear and accurate history of changes made.
