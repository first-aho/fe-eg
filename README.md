# fe-eg

## Workflow

see `.github/workflows/static.yml`

## Set environment variable

At the repository page, click `Settings` -> `Secrets and variables` -> `Actions` -> `Variables` tab -> `Manage environments` -> `github-pages` -> `Add variable`.

In this example, the name of env var is `BACKEND_BASE_URL`.

## Enable Github Page

At the repository page, click `Settings` -> `Pages`, change `Deploy from a branch` to `Github Actions`.

## Create PAT

create PAT with `repo`, `workflow` and `read:org`
