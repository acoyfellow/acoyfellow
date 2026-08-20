# hello (new) world

I'm Jordan. I work [@cloudflare](https://github.com/cloudflare) on the agent experience team.

I build small tools for AI agents: memory, sandboxes, proof, control surfaces, and Cloudflare infrastructure. I write about it at [coey.dev](https://coey.dev).

## now

The operating environment, then the pieces it needs.

- [**my-ax**](https://github.com/acoyfellow/my-ax): a personal AI agent operating environment you self-host on Cloudflare. Chat, desk, recipes, machines, and a factory that classifies GitHub issues. A human still merges.
- [**terrarium**](https://terrarium.coey.dev): one bounded task → one child run → one inspectable result. Status, receipts, cancellation, callbacks.
- [**terraloop-mode**](https://github.com/acoyfellow/terraloop-mode): no child agents spawn until a contract is locked and a driver loop exists. A Pi extension.
- [**pantry**](https://pantry.coey.dev): a capability-scoped recipe store. Agents fetch exact saved code. Pantry never runs it.
- [**gateproof**](https://gateproof.dev): the proof contract. `plan.ts` is forbidden to the worker. Implementation may change. The gate does not.
- [**tollgate**](https://github.com/acoyfellow/tollgate): a local HTTP policy gate. Every request meets a rule before it leaves the machine.
- [**airlock**](https://github.com/acoyfellow/airlock): push a candidate, run tests on a dark URL, promote live only if a signed proof verifies. Fail closed.

## coordination (this week)

Tiny public primitives. Not a chat. Not a platform.

- [**hold**](https://github.com/acoyfellow/hold): a job waits. A runner claims once. There is no poll.
- [**lease**](https://github.com/acoyfellow/lease): subscribe a pantry recipe to a peer outbox for a bounded time.
- [**room**](https://github.com/acoyfellow/room): disposable URL. Mint a room.
- [**trick**](https://github.com/acoyfellow/trick): two URLs. Write yours. Read theirs.
- [**cell**](https://github.com/acoyfellow/cell): invoke a named tenant. Get result and evidence. Do not receive source.
- [**tip**](https://github.com/acoyfellow/tip): commits and trees. History is the product.

## proof

The model proposes. Something it does not own decides.

- [**agent-admit**](https://github.com/acoyfellow/agent-admit): map of where an admitter the model does not own is live.
- [**witness-pi**](https://github.com/acoyfellow/witness-pi): a coding agent should not decide its own work is done.
- [**mutant**](https://github.com/acoyfellow/mutant): mutation testing for TypeScript. Finds code tests run but never check.
- [**keel**](https://github.com/acoyfellow/keel): a candidate is identified by content and only promoted when its proof checks against trusted keys.
- [**cloudeval**](https://github.com/acoyfellow/cloudeval): run model evals, compare results, ship shareable reports.
- [**visual-diff**](https://github.com/acoyfellow/visual-diff) · [**semantic-diff**](https://github.com/acoyfellow/semantic-diff) · [**vitest-visual-diff**](https://github.com/acoyfellow/vitest-visual-diff): fail-closed visual and accessibility verdicts.
- [**corrections-to-gates**](https://github.com/acoyfellow/corrections-to-gates): mine agent-correction exhaust into deterministic gates.
- [**molt**](https://molt.coey.dev): an agent writes a tool, the loop injects a fault, a separate verifier decides.

## memory & continuity

- [**deja**](https://deja.coey.dev): repository-scoped memory. Agents learn from failures; deja remembers.
- [**wake**](https://github.com/acoyfellow/wake): sessionless work continuity and handoffs.
- [**imprint**](https://imprint.coey.dev): immutable commit-bound repository context.
- [**cache-layer**](https://github.com/acoyfellow/cache-layer): verified recipe routing for AI agents on Cloudflare.

## agent tools

- [**echo**](https://echo.coey.dev): drive a browser tab you are already signed into over MCP.
- [**unsurf**](https://unsurf.coey.dev): turn any website into a typed API. Scout, replay, auto-heal.
- [**agentcast**](https://github.com/acoyfellow/agentcast): live browser sessions for AI agents.
- [**machinectl**](https://github.com/acoyfellow/machinectl): MCP server that lets AI control your machine from any device.
- [**loops-yaml**](https://github.com/acoyfellow/loops-yaml): a loop is a schedule plus a command.
- [**mcp-code-mode**](https://github.com/acoyfellow/mcp-code-mode): wrap an MCP server with fail-closed search and sandboxed multi-tool execution.

## pi

Extensions for [Pi](https://github.com/earendil-works/pi-coding-agent).

- [**witness-pi**](https://github.com/acoyfellow/witness-pi)
- [**hashline-pi**](https://github.com/acoyfellow/hashline-pi)
- [**mutex-pi**](https://github.com/acoyfellow/mutex-pi)
- [**auto-thinking-pi**](https://github.com/acoyfellow/auto-thinking-pi)
- [**terraloop-mode**](https://github.com/acoyfellow/terraloop-mode)

## sandboxes

- [**lab**](https://lab.coey.dev): isolated execution on Worker Loaders; every step becomes a shareable trace.
- [**cloudbox**](https://cloudbox.coey.dev): durable Cloudflare computers for agents.
- [**cloudshell**](https://cloudshell.coey.dev): browser terminal in the cloud.
- [**filepath**](https://myfilepath.com): background agent environment. Workspaces, sandboxed filesystems, your keys.

## surfaces

- [**mote**](https://mote.coey.dev): programmable local-first Mac control shell.
- [**tuiport**](https://tuiport.coey.dev): real SSH apps with OpenTUI in a Cloudflare Container.
- [**svelte-hono**](https://svelte-hono.coey.dev): Svelte 5 SSR in a Hono Worker, without SvelteKit.
- [**kumo-compiler**](https://kumo-compiler.coey.dev): author once in canonical React; compile to Vue, Svelte, and Solid.
- [**up**](https://up.coey.dev): a folder becomes an immutable, Access-protected URL on a company's own Cloudflare account.
- [**t2t**](https://t2t.now): local push-to-talk dictation for macOS.

## more

Older catalogs, games, and Cloudflare pattern libraries stay in the repos. Favorites from writing: [Patience](https://coey.dev/patience) · [Campfire](https://coey.dev/campfire) · [Prompts Are Wishes](https://coey.dev/prompts-are-wishes) · [Liquid Primitives](https://coey.dev/liquid-primitives) · [Worker Loaders as a Place](https://coey.dev/worker-loaders).

[coey.dev](https://coey.dev) · [blog](https://coey.dev/blog) · [@acoyfellow](https://twitter.com/acoyfellow)
