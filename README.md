# Kyle Clouthier

**Now building: [SECOND STRIKE](https://secondstrike.io)**, a free real-time world war on a 3D globe of the real Earth, played by people and AI models. Up to 200 players per war, AI leaders that remember you, and a doomsday clock that wipes out whoever strikes midnight.
[Play it](https://secondstrike.io) · [watch AI models fight live](https://secondstrike.io/#/ai) · [the Midnight Index](https://secondstrike.io/midnight) (what AI models do with the nuclear button) · [Humans vs AI](https://secondstrike.io/humans) · [press kit](https://secondstrike.io/press)

**[secondstrike-agents](https://github.com/KyleClouthier/secondstrike-agents)** (open source): put your own AI agent in command of a nation. MCP server, starter bots in JavaScript and Python, and an LLM agent for any OpenAI-compatible model.


Distributed systems and verifiable computing. I build tested systems whose
outputs carry a proof anyone can reproduce byte-for-byte.

**[bitrep](https://github.com/KyleClouthier/bitrep)** (open source) —
order-invariant, bit-identical floating-point reductions for **Rust, JavaScript,
and Python** (`cargo add` / `npm install` / `pip install bitrep`). Exact
mergeable sums with a canonical 289-byte state: proved in Lean, checked by
Kani, fuzzed against an independent oracle, and pinned to one SHA-256 across
x86-64, ARM64, Windows and WebAssembly in CI on every commit — a receipt hashed
in Python matches one hashed in JavaScript, byte for byte.
[Try it in your browser](https://simgen.dev/bitrep/) — your device joins the
proof.

**[kani-vacuity-demo](https://github.com/KyleClouthier/kani-vacuity-demo)**
(open source) — one deliberately broken function, five harness styles, and the
question of whether a passing proof proves anything. Four of the five report
`VERIFICATION:- SUCCESSFUL`; only the fully symbolic one finds the bug. Runs in
under a second. Written alongside a
[proposal](https://github.com/model-checking/verify-rust-std/issues/617) to the
Rust standard library verification effort: pair a reachability witness with
every assumption, and require every harness to fail against at least one mutant.

**Cairn** (closed source — [overview](https://simgen.dev/cairn/)) — serverless
trust for meshes that keeps admitting and revoking when the server, CA, or
cloud is gone. Validated live transatlantic; post-quantum end to end.

Working languages and tools: Rust, Lean 4, Python, TypeScript; Kani, CBMC,
Verus, Z3 for machine-checked proofs about real code.

More at [simgen.dev](https://simgen.dev) — exact arithmetic, verifiable
compute, and case studies.

Currently: open to **remote** distributed-systems, verifiable-compute and
security-engineering roles, and to short design-partner pilots.
Reach me at kyle@simgen.dev.
