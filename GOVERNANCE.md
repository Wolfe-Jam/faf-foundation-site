# FAF Foundation — Governance

*Stewarding the FAF Foundational AI-Context Layer: open, vendor-neutral **context**, **memory**, and **agent** formats for AI.*

> This document is the canonical reference for how the FAF formats are governed — change control, decisions, versioning, and IANA stewardship. It doubles as the source for the Governance section of [foundation.faf.one](https://foundation.faf.one).

## 1. The Foundation
The FAF Foundation is the institutional steward of the FAF formats — it maintains the specifications, the reference implementations, and the formats' registrations with standards bodies. The Foundation runs an open, public contribution process and is evolving toward broader multi-stakeholder governance as adoption grows.

## 2. Scope — what the Foundation governs
- The three FAF media types: `.faf` (context) · `.fafm` (memory) · `.fafa` (agent).
- The `/.well-known/faf` discovery URI.
- The specification, `draft-wolfe-faf-format`, and its evolution.
- Reference implementations and official SDKs (TypeScript, Python, Rust).
- Stewardship of the formats' IANA registrations.

## 3. Change control
**Change controller: FAF Foundation** — contact `team@faf.one`. A single entity holds change control for every FAF format and registration, giving a stable, unambiguous point of authority that is consistent across all IANA records. The Foundation's working repository is the canonical location for specification work and public decision-making.

## 4. Decision process
Substantive changes follow an open, four-stage path, recorded in public:
1. **Suggest** — open an issue or discussion.
2. **Discuss** — public review and feedback.
3. **Implement** — pull request and review.
4. **Release** — versioned publication.

## 5. Versioning & stability
FAF formats use semantic versioning. Backward compatibility is a primary goal: registered media types remain valid across revisions, and consumers treat unknown fields as forward-compatible. Breaking changes require a new major version and a documented migration path.

## 6. IANA stewardship
The Foundation is the change controller of record for the FAF registrations:

| Format | Media type | Registered |
|---|---|---|
| Context | `application/vnd.faf+yaml` | 2025-10-30 |
| Memory | `application/vnd.fafm+yaml` | 2026-05-13 |
| Agent | `application/vnd.fafa+yaml` | 2026-06-26 |

The specification `draft-wolfe-faf-format` additionally requests standards-tree registration and registration of the `/.well-known/faf` discovery URI.

## 7. Licensing
The FAF specification and reference implementations are MIT-licensed, for broad adoption.

## 8. Adoption — the basis for stewardship
FAF is in production use across the MCP server family (Claude, Grok, Gemini), the package registries (npm, PyPI, crates.io), and IDE/agent integrations. This deployment is the evidence base on which the Foundation's stewardship — and its evolving governance — rests.

## 9. Participation & sponsorship
Contribution is open to all through the Foundation's public repository. The Foundation is seeking founding sponsors to support long-term sustainability and standards work — early supporters help shape the roadmap.

## 10. Model
The Foundation follows the established open-foundation model (in the spirit of the Rust Foundation): a neutral steward maintaining an open standard through a transparent, public process.

## Contact
FAF Foundation · `team@faf.one` · [foundation.faf.one](https://foundation.faf.one)
