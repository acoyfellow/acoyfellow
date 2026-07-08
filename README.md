# hello (new) world

I'm Jordan. I work [@cloudflare](https://github.com/cloudflare) on the agent experience team.

I build small tools for AI agents: memory, sandboxes, control surfaces, browser automation, and Cloudflare infrastructure. I write about it at [coey.dev](https://coey.dev).

## what I'm building now

Small, composable surfaces where people and agents can share context, delegate work, and ship things on Cloudflare.

- [**terrarium**](https://terrarium.coey.dev): one bounded task → one child agent → one inspectable result. One-level orchestration with containment probes and a public red-team demo.
- [**my-ax**](https://github.com/acoyfellow/my-ax): a personal AI agent operating environment you self-host on Cloudflare.
- [**kumo-compiler**](https://kumo-compiler.coey.dev): author a component once in canonical React; compile to genuine native Vue, Svelte, and Solid.
- [**up**](https://github.com/acoyfellow/up): put a company's private web online on its own Cloudflare account. A folder becomes an immutable, Access-protected URL.
- [**loop**](https://loop.coey.dev): a personal chatbot that ships working Svelte artifacts and remembers what you tell it. Rolling memory backed by Cloudflare Vectorize.
- [**loops-yaml**](https://github.com/acoyfellow/loops-yaml): tiny scheduled or on-demand command loops, plus session-scoped recurring prompts for Pi and OpenCode.
- [**mote**](https://mote.coey.dev): a programmable, local-first Mac control shell. Edit a Svelte file; the native menu-bar interface changes immediately.
- [**tuiport**](https://tuiport.coey.dev): real SSH applications built with OpenTUI and deployed in a Cloudflare Container.
- [**svelte-hono**](https://svelte-hono.coey.dev): Svelte 5 SSR and hydration in a Hono Worker, without SvelteKit.

## memory & continuity

- [**deja**](https://deja.coey.dev): persistent memory for agents. Agents learn from failures. Deja remembers.
- [**wake**](https://github.com/acoyfellow/wake): sessionless work continuity and handoffs for AI coding agents.
- [**imprint**](https://imprint.coey.dev): immutable commit-bound repository context so an LLM can answer, compare, promote, and roll back against exact code versions.

## research & multi-agent

- [**argus**](https://argus.coey.dev): a sourced web research agent that gathers evidence, follows weak spots, and returns a clear report with links.
- [**orbit**](https://orbit.coey.dev): bounded public-source monitor that turns releases and posts into evidence-linked briefs.
- [**pai-agent**](https://github.com/acoyfellow/pai-agent): research and analysis agent as a Cloudflare Durable Object with shell access, tool use, and WebSocket streaming.
- [**swarm**](https://swarm.coey.dev): run one AI task across a batch of inputs on Cloudflare Workers, Durable Objects, and Workers AI.
- [**prism**](https://github.com/acoyfellow/prism): parallel experiment runner on Cloudflare. Orchestrator, sub-agents, and sandboxed Linux containers.
- [**effect-agents**](https://effect-agents.coey.dev): five agent patterns proven with Effect v4 — parallelism, streaming cancellation, approvals, typed errors, and MCP exposure.
- [**parley**](https://github.com/acoyfellow/parley): two AI models debate until they agree on a plan.
- [**ditto**](https://ditto.coey.dev): run multiple Cloudflare AI models simultaneously. Merge every output with consensus.

## agent tools

- [**echo**](https://echo.coey.dev): drive a browser tab you're already signed into over MCP, without handing an agent your password or session token.
- [**unsurf**](https://unsurf.coey.dev): turn any website into a typed API. Scout, replay, auto-heal.
- [**agentcast**](https://github.com/acoyfellow/agentcast): live browser sessions for AI agents. Watch them work in real time.
- [**machinectl**](https://github.com/acoyfellow/machinectl): MCP server that lets AI control your machine from any device.
- [**chomp**](https://chomp.coey.dev): OpenAI-compatible proxy for free LLM providers. Bring your keys. We route the rest.
- [**anytool**](https://anytoolhq.com): give your AI agent infinite tools with one API call.
- [**inbox.dog**](https://inbox.dog): Gmail OAuth for AI agents. Read, write, search, and send with one integration.
- [**firestore-mcp-kit**](https://github.com/acoyfellow/firestore-mcp-kit): build secure, typed MCP tools backed by Firestore with explicit Zod schemas.

## sandboxes & environments

- [**lab**](https://lab.coey.dev): isolated execution and traces for AI agents. Sandboxed Dynamic Workers on Cloudflare Worker Loaders; every step becomes a shareable trace.
- [**cloudbox**](https://cloudbox.coey.dev): synthetic cloud computers for training and evaluating long-horizon agents on Cloudflare.
- [**cloudshell**](https://cloudshell.coey.dev): browser-based terminal and dev environment in the cloud. Instant access to a full shell from anywhere.
- [**filepath**](https://myfilepath.com): your own background agent environment. Workspaces, sandboxed filesystems, harness registry, and your own model keys.
- [**cloudterm**](https://github.com/acoyfellow/cloudterm): DOM-rendered web terminal emulator with custom ANSI parsing and latency prediction.
- [**mcpu**](https://github.com/acoyfellow/mcpu): MCP control surface for a Cloudflare Artifacts repo. Inspect, edit, commit, and redeploy a Worker.
- [**promptlog**](https://github.com/acoyfellow/promptlog): Dynamic Worker Loader with sandboxed code execution.
- [**ffmpeg-container**](https://github.com/acoyfellow/ffmpeg-container): tiny Cloudflare Containers hello world proving ffmpeg runs at the edge.

## observability & devices

- [**glance**](https://github.com/acoyfellow/glance): see your projects move. A local-first dashboard that observes work by people and agents as a live feed, color, sound, and a responsive 3D orb.
- [**desk**](https://github.com/acoyfellow/desk): a personal app store for tiny edge devices. `git push` installs apps; MCP lets agents use the device as an out-of-band human I/O surface.
- [**t2t**](https://t2t.now): voice-to-text with MCP support and system-wide dictation.
- [**living-artifact**](https://github.com/acoyfellow/living-artifact): physical and digital artifacts and tiny devices, with Cloudflare-hosted firmware OTA and health-gated rollback.
- [**anvil**](https://anvil.coey.dev): animations agents can write. Lottie + three.js in one JSON dialect, on Cloudflare Workers.

## proof & security

- [**gateproof**](https://gateproof.dev): E2E testing harness. Observe logs, run actions, assert results.
- [**agent-human-bridge**](https://github.com/acoyfellow/agent-human-bridge): auditable agent and human software-building protocol designed to pass a human safety review.
- [**repo-audit**](https://repo-audit.coey.dev): deterministic repo scoring across 11 quality dimensions.
- [**cf-tutorial**](https://cf-tutorial.coey.dev): 95 questions to prove you know Cloudflare.
- [**vet**](https://github.com/acoyfellow/vet): CASA Tier 2 / OWASP ASVS security scanner.
- [**deadlint**](https://github.com/acoyfellow/deadlint): find dead public methods on Workers DurableObject / RpcTarget / Agent classes, plus structural clones. The linter layer above knip/oxlint.
- [**ascii-smuggler**](https://github.com/acoyfellow/ascii-smuggler): Unicode smuggling and steganography toolkit for security research.
- [**gate-review**](https://github.com/acoyfellow/gate-review): red-team your gates before implementing them.

## cloudflare patterns

- [**svelte-edge**](https://svelte-edge.coey.dev): agent-generated Svelte 5 UI compiled on Cloudflare Workers into inline edge bundles.
- [**capa**](https://capa.coey.dev): third-party APIs as proof-carrying Cloudflare service bindings.
- [**UserDO**](https://github.com/acoyfellow/UserDO): per-user Durable Objects as data pods.
- [**JotDB**](https://jotdb.coey.dev): durable state without migrations. One Durable Object per user, tenant, room, or actor.
- [**blaze**](https://github.com/acoyfellow/blaze): real-time documents on Cloudflare. Firestore feel, Cloudflare price.
- [**fleet-pattern**](https://github.com/acoyfellow/fleet-pattern): hierarchical Durable Objects with ordered fan-out.
- [**workflow-live**](https://github.com/acoyfellow/workflow-live): real-time workflow monitoring on the edge.
- [**cache-sync**](https://github.com/acoyfellow/cache-sync): edge cache invalidation that actually scales.
- [**tiny**](https://github.com/acoyfellow/tiny): real-time collaborative todos with TinyBase + Durable Objects.
- [**bio**](https://github.com/acoyfellow/bio): single-button WebAuthn auth on Cloudflare.
- [**ironalarm**](https://github.com/acoyfellow/ironalarm): reliable task scheduling for Cloudflare Durable Objects.
- [**ai-connect**](https://github.com/acoyfellow/ai-connect): minimal zero-dependency primitive for configuring and calling AI inference endpoints.
- [**remote**](https://remote.coey.dev): barebones starter for authenticated apps with persistent state on the edge.
- [**share**](https://share.coey.dev): temporary, resumable file shares on Cloudflare Workers, Durable Objects, R2, and Turnstile.
- [**flue-snippets**](https://github.com/acoyfellow/flue-snippets): real, runnable Flue agents on Cloudflare. Every snippet ships an E2E test that deploys, asserts, and tears down.
- [**optkit**](https://github.com/acoyfellow/optkit): email subscriber management for Cloudflare Workers.

## games

- [**vibe-cdn**](https://vibe-cdn.coey.dev): browser games on Cloudflare's edge.
- [**arcade**](https://arcade.coey.dev): neon hovercraft survival. A browser game built and deployed on Cloudflare.

## running

- [**phonesites**](https://phonesites.com): build a website in 5 minutes from any device.
- [**signedseal**](https://signedseal.com): self-custody e-signatures.
- [**formdrift**](https://formdrift.com): voice, photo, and document input for web forms.
- [**formwing**](https://formwing.com): AI outreach from contact forms.

## writing

Some favorites from [coey.dev/blog](https://coey.dev/blog).

- [**Patience: You've Never Controlled Anything**](https://coey.dev/patience): what Memento taught me about prompting agents.
- [**Campfire: The Oldest Protocol**](https://coey.dev/campfire): every storytelling medium had a context window. We've always been writing prompts, we just called them stories.
- [**Prompts Are Wishes**](https://coey.dev/prompts-are-wishes): every prompt is a hypothesis. The guardrails are somewhere else.
- [**Liquid Primitives**](https://coey.dev/liquid-primitives): five parts of your stack to hold loosely.
- [**Worker Loaders as a Place**](https://coey.dev/worker-loaders): Dynamic Workers clicked when I stopped thinking about the API and started thinking about the room.

More at [coey.dev/blog](https://coey.dev/blog).

## find me

[coey.dev](https://coey.dev) · [blog](https://coey.dev/blog) · [@acoyfellow](https://twitter.com/acoyfellow)
