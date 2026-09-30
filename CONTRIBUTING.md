# Contributing to Sanoma

Thanks for helping build Sanoma. This guide applies to every public repo in the Sanoma-AI org unless a repo says otherwise.

## Contribution terms

Terms depend on the repo's license:

| Repos | License | Terms |
| --- | --- | --- |
| `sanoma`, `provider-bridge`, `terraform-provider-sanoma`, `registry`, `company-template` | Apache-2.0 (or MPL-2.0 for `terraform-provider-sanoma`) | Developer Certificate of Origin (DCO) |
| `platform` | FSL-1.1-Apache-2.0; `ee/` commercial | Contributor License Agreement (CLA) |

### DCO (Apache-licensed repos)

Sign off every commit to certify the [Developer Certificate of Origin](https://developercertificate.org/):

```
git commit -s
```

This adds a `Signed-off-by: Your Name <you@example.com>` line. Pull requests with unsigned commits cannot be merged.

### CLA (`platform`)

Contributions to `platform` require a signed Contributor License Agreement before they can be merged. The CLA process will be linked here before launch.

## Tests against live vendors

Connector tests that call real vendor sandboxes (Mercury, Gusto, Okta and others) do not run automatically on pull requests from forks. Vendor sandbox credentials are never exposed to fork PRs. A maintainer runs live tests by adding a label to the pull request after reviewing the change.

## Connectors

First-party connectors live in the `sanoma` monorepo. Community connectors live in their authors' own repos, named `sanoma-connector-<vendor>`, and are listed through [`registry`](https://github.com/Sanoma-AI/registry).

## Conduct and security

- Follow the [Code of Conduct](CODE_OF_CONDUCT.md).
- Report vulnerabilities privately as described in [SECURITY.md](SECURITY.md), not in public issues.
