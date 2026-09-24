# oaslananka-agent runtime

Public GitHub Actions runtime distribution for `oaslananka-agent`.

This repository is a generated distribution surface. It contains only the reusable execution workflow, the bundled runtime action, and provenance metadata needed by public and private target repositories. Control-plane source, policy implementation, deployment code, and credentials are not distributed here.

Use the managed `v1` tag from a target repository:

```yaml
jobs:
  agent:
    uses: oaslananka/oaslananka-agent-runtime/.github/workflows/agent-execution.yml@v1
```

`runtime-manifest.json` records the exact private source commit and SHA-256 digest of every distributed runtime file.
