# CLAUDE.md

This repository is Agxium's **public issue, feedback, roadmap, milestone, and backlog hub**. It is not a product source repository.

## Public-data boundary

Everything written here is public. Never publish secrets, credentials, tokens, private URLs, raw request/response bodies, customer or patient data, payment data, KYC/KYB/KYT evidence, internal logs, private source code, or security-sensitive infrastructure details.

Suspected security vulnerabilities must not be filed publicly. Follow `SECURITY.md`.

## AI-agent reporting rules

When an AI agent is asked to report an Agxium problem publicly:

1. Search this repository for an existing materially equivalent issue first.
2. Prefer updating an existing issue over creating a duplicate.
3. Report observed facts, reproduction steps, expected behavior, and safe environment/version details.
4. Never invent a root cause. If the root cause is not verified, state that it is not yet confirmed.
5. Never expose private repository content or private implementation details in the public report.
6. Use the appropriate issue form/category when available.

## Triage rules

When a team member or approved AI agent reviews the public inbox:

1. Determine whether the report is actionable, duplicate, needs information, not reproducible, or not planned.
2. If engineering work is required, identify the owning private repository from verified evidence.
3. Create a detailed private engineering issue in that repository containing the public issue reference, verified current gap/root cause when known, affected files when verified, implementation guidance, acceptance criteria, tests, and a local AI-agent prompt.
4. The private engineering issue must link back to the public issue.
5. Do not expose the private issue URL, private repository details, source snippets, or sensitive diagnostics back into the public issue unless explicitly safe and approved.
6. Public status updates should be product-facing and concise.

## Roadmap and milestones

- Public milestones describe planned product targets.
- Open issues form the public backlog.
- Milestone assignment is planning information, not a contractual delivery commitment.
- Do not duplicate roadmap state in Markdown when GitHub Issues/Milestones already represent it.

## Repository changes

Keep this repository lightweight. Do not add product application code, server code, databases, telemetry collectors, background workers, or paid observability dependencies. GitHub itself is the system of record for this public hub.
