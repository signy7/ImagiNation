# Security

[English](SECURITY.md) · [简体中文](docs/zh-CN/SECURITY.md) · [Project home](README.md)

## Supported surface

Security review applies to the current default-branch documents, links, static assets, and GitHub templates. IFD excludes executable deployments. Older snapshots are not maintained separately.

Review covers malicious links, exposed secrets, unsafe SVG content, and repository-account access.

## Credentials and privacy

- Never supply an API key, password, access token, or identity document to this project.
- Complete the GitHub access test by self-attestation; do not submit screenshots or credentials.
- No project software collects data. GitHub and the linked badge service operate their own services; loading a remote badge may send a normal image request to that service.
- Treat unexpected downloads, login forms, API endpoints, and requests to “activate” ImagiNation as outside the documented project.

## Reporting

For a broken link, unsafe image, misleading claim, or other non-sensitive problem, open a documentation Issue and describe the affected file. Do not include live secrets or other people's private information.

Revoke or rotate exposed credentials through the issuing service before reporting them. For private reports, use **Security → Report a vulnerability** when available. Otherwise, use GitHub's reporting or support controls for platform abuse or account compromise. Keep sensitive details out of public Issues.

## Review rules

Static SVGs must have no scripts, event handlers, embedded active content, or external resource references. Diagrams must not contain clickable traps. Contributions must not introduce executable workflows, business code, dependency manifests, or tracking.

Maintainers triage reports as capacity permits. No bug bounty or response-time commitment is offered.
