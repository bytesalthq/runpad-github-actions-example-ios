# Runpad - Github Actions Example iOS

This repository demonstrates the integration of [Bytesalt Runpad](https://bytesalt.com/) with GitHub Actions for an iOS app.

## Setup

1. Generate CI client credentials by following the [CI Integration guide](https://bytesalt.com/docs/runpad/ci-integration/generate-ci-client-credentials).
2. Store the generated credentials as GitHub secrets in your repository:

- `RUNPAD_CLIENT_ID`
- `RUNPAD_CLIENT_SECRET`

  Refer to [this Github documentation](https://docs.github.com/en/actions/security-guides/using-secrets-in-github-actions#creating-secrets-for-a-repository) for detailed instructions.

3. Check the .github/workflows/build-and-test.yaml file for a reference configuration. Update it with your own Runpad project ID and build configurations.
