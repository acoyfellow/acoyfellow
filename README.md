# hello (new) world

I'm Jordan. I work [@cloudflare](https://github.com/cloudflare) on the agent experience team.

I build small, sharp systems for AI agents: memory, sandboxes, control surfaces, browser automation, and Cloudflare-native app patterns.

## current thread

- [desk](https://github.com/acoyfellow/desk) — a personal app store for tiny edge devices. `git push` installs apps; MCP lets agents use the device as an out-of-band human I/O surface.
- [living-artifact](https://github.com/acoyfellow/living-artifact) — experiments around physical/digital artifacts and tiny devices.
- [terrarium](https://github.com/acoyfellow/terrarium) — one-level orchestration harness for composable AI subagents.
- [wake](https://github.com/acoyfellow/wake) — sessionless work continuity and handoffs for AI coding agents.
- [deja](https://github.com/acoyfellow/deja) — persistent memory for agents. Agents learn from failures; Deja remembers.
- [mcpu](https://github.com/acoyfellow/mcpu) — MCP control surface for a Cloudflare Artifacts repo.
- [cloudshell](https://github.com/acoyfellow/cloudshell) — your personal terminal in the cloud. Deploy in seconds, access anywhere.
- [filepath](https://github.com/acoyfellow/filepath) — personal Cloudflare-hosted development environment. Work lives in conversations, not terminal tabs.
- [agent-human-bridge](https://github.com/acoyfellow/agent-human-bridge) — auditable agent↔human software-building protocol designed to pass a human safety review.

## agent infrastructure

- [lab](https://lab.coey.dev) — sandboxed isolates on Cloudflare Workers with typed capabilities. Effect + Worker Loaders.
- [capa](https://github.com/acoyfellow/capa) — proof-carrying Cloudflare service bindings for third-party APIs.
- [pai-agent](https://github.com/acoyfellow/pai-agent) — research and analysis agent as a Cloudflare Durable Object with shell access, tool use, and WebSocket streaming.
- [prism](https://github.com/acoyfellow/prism) — parallel experiment runner on Cloudflare: orchestrator, sub-agents, sandboxed Linux containers.
- [cloudbox](https://github.com/acoyfellow/cloudbox) — synthetic cloud computers for training and evaluating long-horizon agents. Persona → filesystem → artifacts → collaborators → simulation → retrospective, end-to-end on Cloudflare.
- [svelte-edge](https://github.com/acoyfellow/svelte-edge) — agent-generated Svelte 5 UI compiled on Cloudflare Workers into inline edge bundles.
- [loop](https://github.com/acoyfellow/loop) — orchestrate AI coding loops with guardrails.
- [chomp](https://github.com/acoyfellow/chomp) — OpenAI-compatible proxy across free/cheap model providers.
- [ditto](https://github.com/acoyfellow/ditto) — run multiple AI models in parallel, merge with consensus.
- [parley](https://github.com/acoyfellow/parley) — two AI models debate until they agree on a plan.

## agent tools

- [unsurf](https://github.com/acoyfellow/unsurf) — turn any website into a typed API: scout, replay, auto-heal.
- [t2t](https://github.com/acoyfellow/t2t) — voice-to-text with MCP support and system-wide dictation.
- [agentcast](https://github.com/acoyfellow/agentcast) — live browser sessions for AI agents; watch them work in real time.
- [machinectl](https://github.com/acoyfellow/machinectl) — MCP server that lets AI control your machine from any device.
- [cloudterm](https://github.com/acoyfellow/cloudterm) — DOM-rendered web terminal emulator built on `@chenglou/pretext`.
- [firestore-mcp-kit](https://github.com/acoyfellow/firestore-mcp-kit) — build secure, typed MCP tools backed by Firestore with explicit Zod schemas.
- [inbox.dog](https://inbox.dog) — OAuth for email, simplified. Gmail access tokens without implementing OAuth yourself.
- [anytoolhq](https://anytoolhq.com) — generate tools for AI agents on demand.
- [gateproof](https://github.com/acoyfellow/gateproof) — E2E testing harness: observe logs, run actions, assert results.

## cloudflare patterns

- [ffmpeg-container](https://github.com/acoyfellow/ffmpeg-container) — tiny Cloudflare Containers hello world proving ffmpeg runs at the edge.
- [ai-connect](https://github.com/acoyfellow/ai-connect) — minimal zero-dependency primitive for configuring and calling AI inference endpoints.
- [remote](https://github.com/acoyfellow/remote) — `bun create remote-app my-app`: SvelteKit + auth + DB + Cloudflare deployment.
- [UserDO](https://github.com/acoyfellow/UserDO) — per-user Durable Objects as data pods.
- [blaze](https://github.com/acoyfellow/blaze) — real-time documents on Cloudflare. Firestore feel, Cloudflare price.
- [fleet-pattern](https://github.com/acoyfellow/fleet-pattern) — hierarchical Durable Objects with ordered fan-out.
- [workflow-live](https://github.com/acoyfellow/workflow-live) — real-time workflow monitoring on the edge.
- [cache-sync](https://github.com/acoyfellow/cache-sync) — edge cache invalidation that actually scales.
- [tiny](https://github.com/acoyfellow/tiny) — real-time collaborative todos with TinyBase + Durable Objects.
- [promptlog](https://github.com/acoyfellow/promptlog) — Dynamic Worker Loader with sandboxed code execution.
- [bio](https://github.com/acoyfellow/bio) — single-button WebAuthn auth on Cloudflare.
- [JotDB](https://github.com/acoyfellow/JotDB) — schema-optional key-value database for Durable Objects.
- [edgewire](https://github.com/acoyfellow/edgewire) — Node.js TCP libraries in Cloudflare Workers.
- [cf-tutorial](https://github.com/acoyfellow/cf-tutorial) — 95 questions to prove you know Cloudflare.
- [ironalarm](https://github.com/acoyfellow/ironalarm) — reliable task scheduling for Cloudflare Durable Objects.
- [flue-snippets](https://github.com/acoyfellow/flue-snippets) — real, runnable Flue agents on Cloudflare. Examples teach one product at a time; recipes compose. Every snippet ships an E2E test that deploys, asserts, and tears down.

## security & compliance

- [vet](https://github.com/acoyfellow/vet) — CASA Tier 2 / OWASP ASVS security scanner.
- [repo-audit](https://github.com/acoyfellow/repo-audit) — deterministic repo scoring across 11 quality dimensions.
- [deadlint](https://github.com/acoyfellow/deadlint) — find dead public methods on Workers DurableObject / RpcTarget / Agent classes, plus structural clones. The linter layer above knip/oxlint.
- [ascii-smuggler](https://github.com/acoyfellow/ascii-smuggler) — Unicode smuggling and steganography toolkit for security research.
- [gate-review](https://github.com/acoyfellow/gate-review) — red-team your gates before implementing them.

## products

- [phonesites](https://phonesites.com) — build websites from any device, no code.
- [signedseal](https://signedseal.com) — self-custody e-signatures.
- [optkit](https://github.com/acoyfellow/optkit) — email subscriber management for Cloudflare Workers.
- [formdrift](https://formdrift.com) — voice, photo, and document input for web forms.
- [formwing](https://formwing.com) — AI contact form outreach at scale.

## find me

[coey.dev](https://coey.dev) · [@acoyfellow](https://twitter.com/acoyfellow)


