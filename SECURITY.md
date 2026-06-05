# Security Policy

## Scope

This policy applies to open-source repositories maintained by [Javan Rasokat](https://github.com/JavanXD) — security research tools, training materials, workshop apps, and community utilities.

If a repository has its own `SECURITY.md`, **that file takes precedence**.

### Actively maintained (examples)

- [Conference Tracker](https://github.com/JavanXD/ConferenceTracker) — static site; no server-side user data
- [Raceocat](https://github.com/JavanXD/Raceocat) — security research tooling
- [ya-pihole-list](https://github.com/JavanXD/ya-pihole-list) — blocklist automation
- [LasVegasNightlifeApp-Workshop](https://github.com/JavanXD/LasVegasNightlifeApp-Workshop) — DEF CON workshop materials
- [HoneyPi](https://github.com/Honey-Pi/HoneyPi) — IoT firmware and installer (see also [Honey-Pi org](https://github.com/Honey-Pi))

## Reporting a vulnerability

**Do not open public GitHub issues for security vulnerabilities.**

### Preferred: private disclosure

1. Open the **affected repository** on GitHub.
2. Go to **Security → Advisories → Report a vulnerability**.
3. Submit a private advisory with reproduction steps and impact.

This keeps details confidential until a fix is ready.

### Fallback

If private reporting is unavailable on a repository, contact via [about.javan.de](https://about.javan.de).

For **HoneyPi**-specific issues, you may also use [honeys@honey-pi.de](mailto:honeys@honey-pi.de).

### Please include

- Affected repository, version, or commit SHA
- Clear steps to reproduce
- Impact assessment (confidentiality, integrity, availability)
- Proof of concept, if available

## Response timeline

| Stage | Target |
|-------|--------|
| Acknowledgement | Within 5 business days |
| Status update | Within 14 business days |
| Fix & disclosure | Coordinated once a remedy is available |

Credit in advisories or release notes is offered unless you prefer to remain anonymous.

## In scope

- Vulnerabilities in code, configuration, or documented deployment paths in maintained repositories
- Unsafe defaults that could harm users in realistic deployments

## Out of scope

- Third-party hosting, CDN, or dependency infrastructure outside this codebase
- Social engineering, physical attacks, or denial-of-service without a code fix
- Issues with no realistic security impact (typos, styling, feature requests)
- Vulnerabilities in abandoned or archived repositories (report anyway — response may be limited)

Thank you for responsible disclosure.
