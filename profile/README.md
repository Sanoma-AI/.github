# Sanoma

Business as Code keeps a company's operational configuration (card limits, time-off policies, access, onboarding steps) in typed code and applies it to vendors like Mercury, Gusto and Okta, with a generated UI over every resource. It applies the infrastructure-as-code model to business tools: an agent drafts each change, policies decide who must approve, and a ledger records what happened.

## Public repositories

- [sanoma](https://github.com/Sanoma-AI/sanoma): open core: schema, planner, Cedar policies, ledger format, MCP server, local studio, CLI, first-party connectors, modules (Apache-2.0)
- [provider-bridge](https://github.com/Sanoma-AI/provider-bridge): Go sidecar loading Terraform/OpenTofu providers (Apache-2.0)
- [registry](https://github.com/Sanoma-AI/registry): connector index with versions, verification tiers and permission scopes
- [company-template](https://github.com/Sanoma-AI/company-template): starting point for a customer's configuration repo (Apache-2.0)
- [docs](https://github.com/Sanoma-AI/docs): product and connector documentation
- [platform](https://github.com/Sanoma-AI/platform): hosted web app, chat agent, approvals, scheduled drift, hosted ledger (source-available, FSL-1.1-Apache-2.0)
