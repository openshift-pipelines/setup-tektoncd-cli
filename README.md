[![use-action][useActionWorkflowBadge]][useActionWorkflow]

`setup-tektoncd-cli`
------------------

GitHub Action to rollout [Tekton CLI (`tkn`)][githubTektonCLI].

# Usage

```yaml
---
jobs:
  setup-tektoncd-cli:
    steps:
      - uses: openshift-pipelines/setup-tektoncd-cli@main
        with:
          version: latest
```

By default the action is set to install `latest` release, for a specific version use the `version` input.

[githubTektonCLI]: https://github.com/tektoncd/cli
[useActionWorkflowBadge]: https://github.com/openshift-pipelines/setup-tektoncd-cli/actions/workflows/use-action.yaml/badge.svg
[useActionWorkflow]: https://github.com/openshift-pipelines/setup-tektoncd-cli/actions/workflows/use-action.yaml
