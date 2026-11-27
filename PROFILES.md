# Optional engineering profiles

The blueprint is guidance for an agent and its human owner. A Markdown rule does not enforce permissions, isolate files, prove a test, grant model access or authorize spending.

## Architecture

Record system boundaries, data ownership, contracts, failure modes, deployment topology, rollback and the simplest viable alternative. Choose a separate service only when deployment, ownership or scaling boundaries justify it.

## Design, UX and motion

Start with the primary user task and the product audience. Define hierarchy, responsive behavior, keyboard and touch behavior, accessible names, loading and failure states, reduced-motion behavior and a truthful fallback for advanced visuals. Use CSS or platform APIs before adding a runtime. Measure real interactions on target devices.

## Security and capability admission

Treat skills, plugins, MCP servers and prompts as untrusted input. Record the upstream, exact revision, digest, permissions, network destinations, data classes, license, cost, tests and rollback before activation. A scanner is evidence for review, not a safety certification. Keep credentials outside the repository.

## Lifecycle and learning

Use explicit states such as planned, implemented, verified, integrated and released. Keep one canonical roadmap. Finish authorized engineering first, then offer a short explanation or optional exercise. Learning mode must not silently change execution authority.

## Provider adapters

Keep the shared constitution provider-neutral and adapters thin. Verify each provider's discovery rules, model names, tool boundaries and native configuration format. Do not claim that a file loaded by one provider is active in another.

