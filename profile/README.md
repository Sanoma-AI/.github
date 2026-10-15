# Sanoma

Business as Code keeps a company's operational configuration (card limits, time-off policies, access, onboarding steps) in typed code and applies it to vendors like Mercury, Gusto and Okta, with a generated UI over every resource. It applies the infrastructure-as-code model to business tools: an agent drafts each change, policies decide who must approve, and a ledger records what happened.

## Public repositories

- [sanoma](https://github.com/Sanoma-AI/sanoma): the runtime, the app (approvals, drift, the ledger), the `npx sanoma` launcher and first-party connectors; everything needed to run it yourself (FSL-1.1-ALv2)
- [provider-bridge](https://github.com/Sanoma-AI/provider-bridge): Go sidecar loading Terraform/OpenTofu providers (FSL-1.1-ALv2)
- [company-template](https://github.com/Sanoma-AI/company-template): starting point for a customer's configuration repo (Apache-2.0)
- [docs](https://github.com/Sanoma-AI/docs): product and connector documentation
