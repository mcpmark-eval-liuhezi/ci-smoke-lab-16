# ci-smoke-lab-16
Throwaway sandbox to prove contribution + CI loop works end to end

## Build artifact

The CI pipeline uploads a build artifact named `demo-build`. It is produced by the `ci.yml` workflow (single job, `workflow_dispatch` trigger) which writes `build-output.txt` and uploads it as the `demo-build` artifact.
