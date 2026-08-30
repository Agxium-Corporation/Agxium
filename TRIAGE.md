# Public Issue Triage

This repository is the single public intake queue for Agxium issues, requests, and roadmap feedback.

## Daily review

Team members or approved AI agents should review new public issues and:

1. search for duplicates;
2. validate that the report contains no sensitive information;
3. request missing reproduction information when needed;
4. classify the report as actionable, duplicate, not reproducible, or not planned;
5. when actionable engineering work is required, create the detailed implementation issue in the verified owning private repository;
6. link the private engineering issue back to the public report;
7. update the public report with a concise product-facing status without exposing private repository details.

## Private engineering handoff

A private implementation issue should contain, when verified:

- the public report reference;
- confirmed current gap or root cause;
- affected files/components;
- implementation instructions;
- acceptance criteria;
- testing requirements;
- local AI-agent implementation prompt.

Never fabricate a root cause to make the handoff appear complete. If investigation is still required, say so explicitly.

## Duplicate handling

Prefer one public issue per materially identical problem. Close later duplicates and point users to the canonical public issue.

## Security and privacy

If a report contains sensitive information or appears security-related, stop public triage and move handling to a private channel. Do not quote or reproduce the sensitive content in comments.
