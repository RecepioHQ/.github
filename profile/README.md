# Recepio

**AI-Native Operations, Communication Platforms & Deterministic MCP Infrastructure**

We build reliable software and agent infrastructure where execution is constrained by explicit policy, deterministic validation, and verifiable runtime evidence.

- **Website:** [recepio.io](https://recepio.io)
- **Founder:** [Tariq Ziad (`@Tariq990`)](https://github.com/Tariq990)

---

## Open-Source Flagship

### [Outbound OS](https://github.com/RecepioHQ/outbound-os) (`MIT`)
Evidence-gated outbound automation with AI/MCP tools, safe-by-default email controls, and deterministic verification before every send.

- **Official MCP Registry:** [Active listing (`v0.2.1`)](https://registry.modelcontextprotocol.io/v0.1/servers?search=outbound-os) · OCI container: `ghcr.io/recepiohq/outbound-os-mcp:0.2.1`
- **Live Interactive Demo:** [Try the Outbound OS Policy Simulator](https://recepiohq.github.io/outbound-os/) (runs entirely in your browser with zero live sends)
- **CLI Quickstart (`Node.js 22+`):**

```bash
npm exec --yes --package=https://github.com/RecepioHQ/outbound-os/releases/download/v0.2.1/outbound-os-0.2.1.tgz -- outbound-os demo --compare
```

---

## Engineering Standards

Every system across Recepio follows fail-closed boundaries:

- **Explicit Authorization** — Model proposals are separated from policy-gated tool execution.
- **Reproducible Verification** — Automated test gates and bounded runtime evidence govern delivery.
- **Security by Default** — Least-privilege credentials, strict redaction, and safe simulation modes.
