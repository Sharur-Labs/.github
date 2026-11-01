# Sharur Labs

**Verified, reproducible proof for AI-found security bugs.**

AI scanners now find vulnerabilities faster than teams can confirm and fix them. Sharur sits between the scanner and the fix: we take findings from any source and return each one as a proof bundle anyone can re-run, or an honest *"not reproduced"* with the reason. Security teams fix what's real instead of triaging noise.

We sell verification, not discovery.

## What we're building

| | Offering | Status |
|---|---|---|
| 🔬 | **Verification Platform** — submit a target and findings from any scanner, bounty report, or researcher; get back a proof bundle per finding with reachability-adjusted severity and root-cause clustering. Verified fixes to follow. | *Link coming soon* |
| 📦 | **Proof Bundle Format** — an open specification for packaging a finding as environment, minimal trigger, oracle evidence, replay seed, and audit trail, so any third party can reproduce it. | *Link coming soon* |
| 🧱 | **Sandbox Runtime** — the open-source containment layer: ephemeral microVMs, no network egress by default, deterministic execution. | *Link coming soon* |

## The lab

Sharur is a lab as much as a product company. Alongside the platform, we run ongoing research into **agentic sandboxes**: how to give AI agents real execution environments while keeping them sealed, scoped, and observable.

Our core bet is **determinism**. When every run inside a sandbox can be replayed exactly, an agent's output stops being a claim and becomes evidence. We're exploring how deterministic execution, record-and-replay, and minimal-effect oracles can turn agentic work into outcomes people can trust and verify independently, starting with security and extending beyond it.

Research notes, open specs, and tooling will be published here as they mature.

## How we work

- **Containment is the floor.** Untrusted code and every exploit attempt run in throwaway microVMs with no network access.
- **Scope is root authority.** Nothing is touched without written authorization.
- **If it can't be replayed, it isn't a proof.**
- **Honest verdicts.** "Not reproduced" is a first-class answer.

Sharur does not build, sell, or distribute exploits. Proof exists only as evidence inside a sandbox.

---

<sub>Sharur Labs · Pre-launch · Watch this org for releases.</sub>
