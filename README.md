# keabyte workflows

Reusable workflows for common CI scenarios.

#### Example usage
```
jobs:
  deploy:
    uses: keabyte/keabyte-workflows/.github/workflows/reactjs-deploy.yml@main
    secrets: inherit
  with:
    input: abc

```