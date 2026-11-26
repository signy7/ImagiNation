# Security

[English](SECURITY.md) · [简体中文](docs/zh-CN/SECURITY.md) · [Project home](README.md)

## Supported surface

ImagiNation is a documentation-only satire project. It has no executable product, model integration, hosted service, account system, package, or runtime dependency. Security review applies to the current default-branch documents, links, static assets, and GitHub templates. Older snapshots are not maintained separately.

“No code, no bugs” is a fictional engineering slogan, not a guarantee of safety. Malicious links, misleading claims, exposed secrets, unsafe SVG content, and repository-account compromise remain possible risks.

## Credentials and privacy

- Never supply an API key, password, access token, or identity document to this project.
- The GitHub access test asks only whether a home page loads; do not submit screenshots or credentials as proof.
- No project software collects data. GitHub and the linked badge service operate their own services; loading a remote badge may send a normal image request to that service.
- Treat unexpected downloads, login forms, API endpoints, and requests to “activate” ImagiNation as outside the documented project.

## Reporting

For a broken link, unsafe image, misleading claim, or other non-sensitive problem, open a documentation Issue and describe the affected file. Do not include live secrets or other people's private information.

If you discover an exposed credential, revoke or rotate it through the issuing service before discussing it. For private reports, use the repository's **Security → Report a vulnerability** option only if it is available. This repository does not promise that private reporting is enabled, and no separate private contact or response-time guarantee is established. If that option is absent, use GitHub's reporting/support controls for platform abuse or account compromise and keep sensitive details out of public Issues.

## Review rules

Static SVGs must have no scripts, event handlers, embedded active content, or external resource references. Diagrams must not contain clickable traps. Contributions must not introduce executable workflows, business code, dependency manifests, or tracking. Fictional benchmark values must remain visibly labelled.

Maintainers review legitimate reports as capacity permits. There is no bug bounty, production SLA, or automated security certification.

---

*Satire describes the imaginary system. Credential handling and honest reporting are real requirements.*
