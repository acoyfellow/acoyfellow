# hello (new) world

I'm Jordan. I work [@cloudflare](https://github.com/cloudflare) on the agent experience team.

I build small tools for AI agents: memory, sandboxes, control surfaces, browser automation, and Cloudflare infrastructure. I write about it at [coey.dev](https://coey.dev).

## what I’m building now

Lately I’m working on small, composable surfaces where people and agents can share context, delegate work, and ship things on Cloudflare.

- [**terrarium**](https://github.com/acoyfellow/terrarium): one bounded task → one child agent → one inspectable result. One-level orchestration for composable subagents, with containment probes and a public red-team demo at [terrarium.coey.dev](https://terrarium.coey.dev).
- [**my-ax**](https://github.com/acoyfellow/my-ax): a personal AI agent operating environment you self-host on Cloudflare. [Live.](https://my-ax.coey.dev)
- [**kumo-compiler**](https://github.com/acoyfellow/kumo-compiler): author a component once in canonical React; compile to genuine native Vue, Svelte, and Solid. [Live gallery.](https://kumo-compiler.coey.dev)
- [**up / inhouse**](https://github.com/acoyfellow/up): put a company’s private web online on its own Cloudflare account. A folder becomes an immutable, Access-protected URL. [Live.](https://up.coey.dev)
- [**loops-yaml**](https://github.com/acoyfellow/loops-yaml): tiny scheduled or on-demand command loops, plus session-scoped recurring prompts for Pi.
- [**mote**](https://github.com/acoyfellow/mote): a programmable, local-first Mac control shell. Edit a Svelte file; the native menu-bar interface changes immediately.
- [**tuiport**](https://github.com/acoyfellow/tuiport): real SSH applications built with OpenTUI and deployed in a Cloudflare Container. [Live demo.](https://tuiport.coey.dev)
- [**svelte-hono**](https://github.com/acoyfellow/svelte-hono): Svelte 5 SSR and hydration in a Hono Worker, without SvelteKit. [Docs.](https://svelte-hono.coey.dev)

## established projects

- [**deja**](https://github.com/acoyfellow/deja): persistent memory for agents. Agents learn from failures. Deja remembers.
- [**echo**](https://github.com/acoyfellow/echo): drive a browser tab you’re already signed into over MCP, without handing an agent your password or session token.
- [**cloudbox**](https://github.com/acoyfellow/cloudbox): synthetic cloud computers for training and evaluating long-horizon agents on Cloudflare.
- [**capa**](https://github.com/acoyfellow/capa): third-party APIs as proof-carrying Cloudflare service bindings.
- [**vibe-cdn**](https://github.com/acoyfellow/vibe-cdn): a Cloudflare game stack for heavy browser games. [Live demo.](https://vibe-cdn.coey.dev)

## writing

Some of my favorites from [coey.dev/blog](https://coey.dev/blog).

- [**Patience: You've Never Controlled Anything**](https://coey.dev/patience): what Memento taught me about prompting agents.
- [**Campfire: The Oldest Protocol**](https://coey.dev/campfire): every storytelling medium had a context window. We've always been writing prompts, we just called them stories.
- [**Prompts Are Wishes**](https://coey.dev/prompts-are-wishes): every prompt is a hypothesis. The guardrails are somewhere else.
- [**Liquid Primitives**](https://coey.dev/liquid-primitives): five parts of your stack to hold loosely.
- [**Worker Loaders as a Place**](https://coey.dev/worker-loaders): Dynamic Workers clicked when I stopped thinking about the API and started thinking about the room.

More at [coey.dev/blog](https://coey.dev/blog).

## agent stack

- [lab](https://lab.coey.dev): sandboxed isolates on Cloudflare Workers with typed capabilities. Effect + Worker Loaders.
- [pai-agent](https://github.com/acoyfellow/pai-agent): research and analysis agent as a Cloudflare Durable Object with shell access, tool use, and WebSocket streaming.
- [prism](https://github.com/acoyfellow/prism): parallel experiment runner on Cloudflare. Orchestrator, sub-agents, sandboxed Linux containers.
- [wake](https://github.com/acoyfellow/wake): sessionless work continuity and handoffs for AI coding agents.
- [desk](https://github.com/acoyfellow/desk): a personal app store for tiny edge devices. `git push` installs apps. MCP lets agents use the device as an out-of-band human I/O surface.
- [svelte-edge](https://github.com/acoyfellow/svelte-edge): agent-generated Svelte 5 UI compiled on Cloudflare Workers into inline edge bundles.
- [chomp](https://github.com/acoyfellow/chomp): OpenAI-compatible proxy across free/cheap model providers.
- [ditto](https://github.com/acoyfellow/ditto): run multiple AI models in parallel, merge with consensus.
- [parley](https://github.com/acoyfellow/parley): two AI models debate until they agree on a plan.
- [mcpu](https://github.com/acoyfellow/mcpu): MCP control surface for a Cloudflare Artifacts repo.
- [cloudshell](https://github.com/acoyfellow/cloudshell): your personal terminal in the cloud. Deploy in seconds, access anywhere.
- [filepath](https://github.com/acoyfellow/filepath): personal Cloudflare-hosted development environment. Work lives in conversations, not terminal tabs.
- [agent-human-bridge](https://github.com/acoyfellow/agent-human-bridge): auditable agent and human software-building protocol designed to pass a human safety review.
- [living-artifact](https://github.com/acoyfellow/living-artifact): physical and digital artifacts and tiny devices.

## agent tools

- [echo](https://github.com/acoyfellow/echo): a Chrome extension plus Cloudflare Worker that makes your logged-in browser tab an MCP target, with origin-pinned sessions and audited plan runs.
- [unsurf](https://github.com/acoyfellow/unsurf): turn any website into a typed API. Scout, replay, auto-heal.
- [agentcast](https://github.com/acoyfellow/agentcast): live browser sessions for AI agents. Watch them work in real time.
- [t2t](https://github.com/acoyfellow/t2t): voice-to-text with MCP support and system-wide dictation.
- [machinectl](https://github.com/acoyfellow/machinectl): MCP server that lets AI control your machine from any device.
- [cloudterm](https://github.com/acoyfellow/cloudterm): DOM-rendered web terminal emulator.
- [firestore-mcp-kit](https://github.com/acoyfellow/firestore-mcp-kit): build secure, typed MCP tools backed by Firestore with explicit Zod schemas.
- [inbox.dog](https://inbox.dog): OAuth for email, simplified. Gmail access tokens without implementing OAuth yourself.
- [anytoolhq](https://anytoolhq.com): generate tools for AI agents on demand.
- [gateproof](https://github.com/acoyfellow/gateproof): E2E testing harness. Observe logs, run actions, assert results.

## cloudflare patterns

- [remote](https://github.com/acoyfellow/remote): `bun create remote-app my-app`. SvelteKit, auth, DB, Cloudflare deployment.
- [UserDO](https://github.com/acoyfellow/UserDO): per-user Durable Objects as data pods.
- [blaze](https://github.com/acoyfellow/blaze): real-time documents on Cloudflare. Firestore feel, Cloudflare price.
- [fleet-pattern](https://github.com/acoyfellow/fleet-pattern): hierarchical Durable Objects with ordered fan-out.
- [workflow-live](https://github.com/acoyfellow/workflow-live): real-time workflow monitoring on the edge.
- [cache-sync](https://github.com/acoyfellow/cache-sync): edge cache invalidation that actually scales.
- [tiny](https://github.com/acoyfellow/tiny): real-time collaborative todos with TinyBase + Durable Objects.
- [promptlog](https://github.com/acoyfellow/promptlog): Dynamic Worker Loader with sandboxed code execution.
- [bio](https://github.com/acoyfellow/bio): single-button WebAuthn auth on Cloudflare.
- [JotDB](https://github.com/acoyfellow/JotDB): schema-optional key-value database for Durable Objects.
- [ironalarm](https://github.com/acoyfellow/ironalarm): reliable task scheduling for Cloudflare Durable Objects.
- [ai-connect](https://github.com/acoyfellow/ai-connect): minimal zero-dependency primitive for configuring and calling AI inference endpoints.
- [ffmpeg-container](https://github.com/acoyfellow/ffmpeg-container): tiny Cloudflare Containers hello world proving ffmpeg runs at the edge.
- [cf-tutorial](https://github.com/acoyfellow/cf-tutorial): 95 questions to prove you know Cloudflare.
- [flue-snippets](https://github.com/acoyfellow/flue-snippets): real, runnable Flue agents on Cloudflare. Every snippet ships an E2E test that deploys, asserts, and tears down.
- [optkit](https://github.com/acoyfellow/optkit): email subscriber management for Cloudflare Workers.

## security & compliance

- [vet](https://github.com/acoyfellow/vet): CASA Tier 2 / OWASP ASVS security scanner.
- [repo-audit](https://github.com/acoyfellow/repo-audit): deterministic repo scoring across 11 quality dimensions.
- [deadlint](https://github.com/acoyfellow/deadlint): find dead public methods on Workers DurableObject / RpcTarget / Agent classes, plus structural clones. The linter layer above knip/oxlint.
- [ascii-smuggler](https://github.com/acoyfellow/ascii-smuggler): Unicode smuggling and steganography toolkit for security research.
- [gate-review](https://github.com/acoyfellow/gate-review): red-team your gates before implementing them.

## running

- [phonesites](https://phonesites.com): build websites from any device, no code.
- [signedseal](https://signedseal.com): self-custody e-signatures.
- [formdrift](https://formdrift.com): voice, photo, and document input for web forms.
- [formwing](https://formwing.com): AI contact form outreach at scale.

## find me

[coey.dev](https://coey.dev) · [blog](https://coey.dev/blog) · [@acoyfellow](https://twitter.com/acoyfellow)
