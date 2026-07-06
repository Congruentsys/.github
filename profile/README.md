# Congruent Systems

**Neurosymbolic AI — software that reasons from structured knowledge, not probabilistic guesses.**

Most AI generates a plausible token stream and asks you to trust it. We build the
other branch: **reasoning is executed, not generated.** A question is answered by an
engine that *derives* the answer over a knowledge graph and hands back the complete
derivation — every rule that fired, down to the seed facts — or it **abstains**.
A claim without a proof is never presented as one.

This is the reasoning core of **NuSy**, our neurosymbolic platform, and of the
NuSy LRM (Large Cognition Model).

## Open source

Our stack is MIT-licensed and developed in the open.

| Project | What it is |
|---|---|
| **[nusy-reasoners](https://github.com/Congruentsys/nusy-reasoners)** | Proof-carrying reasoning engines over Apache Arrow — derivations you can audit, abstention you can trust. The symbolic core. |
| **[nusy-graph](https://github.com/Congruentsys/nusy-graph)** | Document → Y-layer knowledge graph, as a product — the `nusy-grapher` library, CLI, and MCP server. Turns prose into the auditable graph the reasoners run on. |
| **[nusy-kanban](https://github.com/hankh95/nusy-kanban)** | Arrow-native, distributed kanban for multi-agent teams — with a built-in Hypothesis-Driven-Development research workflow. |
| **[noesis-ship](https://github.com/hankh95/noesis-ship)** | Pluggable multi-agent communication platform on NATS (EventBus, KV, object store; WebSocket / MCP / HTTP adapters). |
| **[acf-framework](https://github.com/hankh95/acf-framework)** | A graph-based framework for measuring AI capability against human professional standards. |

## The principle

- **Proof is the currency.** Every answer carries a derivation trace, a provability tag, and provenance.
- **Provability is computed, never asserted.** A heuristic stage is *structurally* unable to mint `Proven` — approximate output can never launder itself into a proof.
- **Abstain loudly.** When it can't prove, it says so, rather than guessing.

## More

🌐 **[congruentsys.com](https://congruentsys.com)**  ·  📄 [Research](https://congruentsys.com/research/)  ·  🧩 [Open source](https://congruentsys.com/open-source/)

<sub>Congruent Systems LLC · North Carolina, USA</sub>
