# Kyle Clouthier

Full-stack developer and marketer in the Ottawa Valley, Canada. I run Clouthier Simulation Labs ([simgen.dev](https://simgen.dev)): websites and apps, security tools for the AI era, and B2B lead generation.

## AgentDecoy

**[AgentDecoy](https://simgen.dev/agentdecoy/)** protects websites and apps from hostile AI agents and scanners with a network of decoys. Fake `.env`, `.git`, AI key and MCP files catch whoever comes looking, every stolen key is traced to the visit it was taken on, and an address caught on one site is refused on logins and forms on every protected site. Search engines and AI search bots are never blocked, and pages always load.

On our own sites, a decoy AWS key was taken by a scanner and used 2 hours 39 minutes later to try to make itself admin. It is now locked out network-wide.

- **[agentdecoy](https://github.com/KyleClouthier/agentdecoy)** (npm `agentdecoy`): one line for Next.js, Vercel, Netlify, Firebase, Cloudflare, Express or any Node server, plus a one-file PHP version. `npx agentdecoy init`
- **[agentdecoy-action](https://github.com/KyleClouthier/agentdecoy-action)**: GitHub Action that scans your site on every deploy for what an AI agent could grab (leaked keys, exposed secret files, open databases, hidden agent text).
- **Free scan and free tripwires** (a fake link, AI key or MCP server that emails you the moment it is used): [simgen.dev/agentdecoy](https://simgen.dev/agentdecoy/)

## PHP2Shell check

- **[php2shell-check](https://github.com/KyleClouthier/php2shell-check)**: check one PHP site or a whole server for the PHP2Shell flaw. The free web version at [simgen.dev/php-patch-check](https://simgen.dev/php-patch-check) has run thousands of checks.
- **[php2shell-action](https://github.com/KyleClouthier/php2shell-action)**: the same check as a GitHub Action, on the Marketplace.

## Also built

- **[SECOND STRIKE](https://secondstrike.io)**: a real-time world war on a 3D globe, played by people and AI agents. Thousands play monthly, and AI builders send their own agents through **[secondstrike-agents](https://github.com/KyleClouthier/secondstrike-agents)** (MCP server and starter bots). Its [Midnight Index](https://secondstrike.io/midnight) compares how AI models handle escalation.
- **[TDot Life](https://tdotlife.app)**: a free life game on real Toronto streets.

<details>
<summary>Earlier open source</summary>

- **[bitrep](https://github.com/KyleClouthier/bitrep):** order-invariant, bit-identical floating-point reductions for Rust, JavaScript and Python, proved in Lean, checked by Kani, and pinned to one SHA-256 across x86-64, ARM64, Windows and WebAssembly.
- **[kani-vacuity-demo](https://github.com/KyleClouthier/kani-vacuity-demo):** five harness styles for one broken function; four report success and only the fully symbolic one finds the bug.

</details>

**Open to remote roles and contracts** in full-stack development, security tooling and business development. Reach me at kyle@simgen.dev or on [LinkedIn](https://www.linkedin.com/in/kyleclouthier/).

Tools: TypeScript, Next.js, Node, Python, PHP, Rust; Firebase, Cloud Run, Firestore, Cloudflare.
