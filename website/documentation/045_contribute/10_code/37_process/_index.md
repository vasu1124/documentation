---
title: Process
remote: https://github.com/gardener/gardener/blob/master/docs/development/process.md
type: contribute
---
# Creating a new Feature

If you want to contribute to the Gardener, please do that always on a dedicated branch on your own fork named after the purpose of the code changes, for example `feature/helm-integration`.
Please do not forget to rebase your branch **regularly**.

If you have finished your work, please create a pull request **based on `master`**. It will be reviewed and merged if no further changes are requested from you.

:warning: Please ensure that your modifications pass the lint checks, formatting checks, static code checks, and unit tests by executing

```bash
make verify
```

:rotating_light: Please run `make generate` whenever you modify the any API within `pkg/apis`.

Please do not file your pull request unless you receive a successful response from here!

## Creating a new Release

Please refer to the [Gardener contributor guide]({{< ref "//documentation/045_contribute/10_code/10-contribution_guide/_index.md" >}}).
