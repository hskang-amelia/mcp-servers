# Disabled workflows

GitHub Actions only runs files under `.github/workflows/`. These workflows were moved here so
that no CI/CD runs in this repository (scheduled jobs and release/publish steps were failing here).

To turn them back on, move the files back:

```sh
git mv .github/workflows-disabled .github/workflows
git rm .github/workflows/README.md
```
