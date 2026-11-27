# Curated capability starting points

This list is deliberately small. Every item remains subject to local review, exact-version pinning, license checks and provider compatibility testing.

| Capability | Purpose | Agents | Cost and security boundary | Official source |
|---|---|---|---|---|
| Vercel Skills | Discover, install and lock agent skills | Claude Code, Codex, Gemini CLI and others | Open-source CLI. Review skill content and telemetry settings before use. | [vercel-labs/skills](https://github.com/vercel-labs/skills) |
| Skillfish | Cross-agent discovery, bundles and restore manifests | Multiple agent CLIs | Open-source CLI. Review registry, GitHub access and telemetry before use. | [knoxgraeme/skillfish](https://github.com/knoxgraeme/skillfish) |
| Gitleaks | Secret scanning for repositories and generated output | Any workflow with a local binary | Local scanning is preferred. Do not upload private source to hosted scanners. | [gitleaks/gitleaks](https://github.com/gitleaks/gitleaks) |
| OSV-Scanner | Dependency vulnerability checks | Any repository | Run against lockfiles and record the version. Review network and database behavior. | [google/osv-scanner](https://github.com/google/osv-scanner) |
| Playwright | Browser and end-to-end verification | Web projects | Use synthetic accounts and isolated browsers. Never attach a personal browser profile. | [microsoft/playwright](https://github.com/microsoft/playwright) |
| axe-core | Automated accessibility checks | Web projects | Treat results as a signal and pair them with keyboard and screen-reader acceptance. | [dequelabs/axe-core](https://github.com/dequelabs/axe-core) |

The public blueprint does not install these tools, claim that they are safe by default or require a specific subscription. Use the provider's current documentation and a reviewed local manifest.
