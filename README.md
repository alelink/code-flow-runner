# code-flow-runner

On-demand ephemeral build machines for code-flow. The workflow is dispatched via the GitHub API, starts a flowrunner, and exits after a few idle minutes.

Nothing is printed in the run log; build logs stay in code-flow.

## Secrets

| Name | Value |
|---|---|
| `FLOW_SERVER` | control plane URL |
| `FLOW_TOKEN` | build node token |
