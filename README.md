# Engineering blueprint — a portable CLAUDE.md

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

The operating manual I give AI coding agents (Claude Code, Codex and similar)
in every repository: engineering principles, an evidence hierarchy, a
risk-scaled workflow, agent coordination, Git, testing, security,
documentation and closeout rules. Project specifics and private paths are
removed; machine-specific settings are `<PLACEHOLDER>`s.

Shared for educational and development use. Read it online at
<https://nikolay-georgiev.dev/open-source/blueprint>.

## Use it

1. Copy [`CLAUDE.md`](CLAUDE.md) to the root of a repository (project rules),
   or to `~/.claude/CLAUDE.md` (your defaults for every project).
2. Fill in section 0: replace every `<PLACEHOLDER>` with your stack, branches
   and the exact commands for running, testing and building.
3. Delete what does not apply (for example the frontend and motion rules in a
   backend repository) and add the rules only your project needs. Project
   rules override the generic ones.
4. Keep it short enough to be read every session. When a rule turns out to be
   wrong, change the file, not the agent's memory.

## Contributing

Issues and pull requests are welcome. Small, focused changes with a reason
are the easiest to accept; open an issue before a large rewrite.

## License

[MIT](LICENSE) © 2026 Nikolay Georgiev. You may use, copy, modify and
redistribute it, commercially or not, as long as the copyright and license
notice stay with it.
