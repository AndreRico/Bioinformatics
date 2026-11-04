# ADR 0002 — Text under CC BY 4.0, code under MIT

- **Status:** Accepted
- **Date:** 2026-11-03

## Context

The book should be easy to reuse in teaching and in other labs' onboarding material, and its commands should be copyable into analysis scripts without legal friction.

## Decision

Book text under **CC BY 4.0**. Code blocks, workflows, and templates under **MIT** ([LICENSE-CODE](../LICENSE-CODE)).

## Alternatives considered

- **CC BY-SA:** forces derived material to keep the same license, which makes it harder to use inside institutional documentation.
- **All rights reserved:** defeats the purpose of an open handbook.

## Consequences

- Anyone can adapt chapters with attribution.
- Third-party figures cannot be included unless their license allows it; diagrams are drawn in Mermaid instead.
