# Github organisation:

## Github Projects And repositories

Projects naming convention: `<Domain> - <Project Name>`

Repositories naming convention: `<domain>.<project-name>.<repo-name>`

For example:

1. `Utilities - Common`

- Description: This project contains all the common utilities that are used across all the projects.
- Repositories:
  - `utilities.common.utils`
    - tags: `utilities`, `common`, `utils`
  - `utilities.common.logger`
    - tags: `utilities`, `common`, `logger`
  - `utilities.common.config`
    - tags: `utilities`, `common`, `config`
  - ...

2. `Services - Auth`

- Description: This project contains all the services related to authentication.
- Repositories:
  - `services.auth.api`
    - tags: `services`, `auth`, `api`
  - `services.auth.client`
    - tags: `services`, `auth`, `client`
  - `services.auth.server`
    - tags: `services`, `auth`, `server`
  - ...

## Github Repositories Tags

Use some tags to identify the repository's purpose.

For example:

- `utilities`
- `common`
- `utils`
- `logger`
- `config`
- `services`
- `auth`
- `api`
- `client`
- `server`
- ...

## Github Repositories Branches

- `master`
- `develop`

Development branches use the convention `<type>/<name>-<issue>` where `<type>` is comes from the [Conventionals Commits specification](https://www.conventionalcommits.org/en/v1.0.0/#summary) and `<name>` is a short description of the feature or fix.

## Github Pull Requests

Use the [Pull Request template](<../PR Templates/main-pr-template.md>) to create a PR and add a reference to the issue number in the description.

## Github Commits

Use the [Conventionals Commits specification](https://www.conventionalcommits.org/en/v1.0.0/#summary) to write commit messages and add a reference to the issue number in footer.
