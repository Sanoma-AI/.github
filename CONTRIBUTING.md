# Contributing to Sanoma

Thanks for helping build Sanoma. This guide applies to every public repo in the Sanoma-AI org unless a repo says otherwise.

## Contribution terms

Every repo takes contributions under the Developer Certificate of Origin:

| Repos | License | Terms |
| --- | --- | --- |
| `sanoma`, `provider-bridge` | FSL-1.1-ALv2 | Developer Certificate of Origin (DCO) |
| `company-template` | Apache-2.0 | Developer Certificate of Origin (DCO) |

### DCO

Sign off every commit to certify the [Developer Certificate of Origin](https://developercertificate.org/):

```
git commit -s
```

This adds a `Signed-off-by: Your Name <you@example.com>` line. Pull requests with unsigned commits cannot be merged.

## Tests against live vendors

Connector tests that call real vendor sandboxes (Mercury, Gusto, Okta and others) do not run automatically on pull requests from forks. Vendor sandbox credentials are never exposed to fork PRs. A maintainer runs live tests by adding a label to the pull request after reviewing the change.

## Connectors

First-party connectors live in the `sanoma` monorepo. A connector moves to its own repo, named `sanoma-connector-<vendor>`, only when someone outside the team maintains it.

## Conduct and security

- Follow the [Code of Conduct](CODE_OF_CONDUCT.md).
- Report vulnerabilities privately as described in [SECURITY.md](SECURITY.md), not in public issues.
