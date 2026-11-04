# ADR 0004 — Examples use public data or stand alone; no private cohort details

- **Status:** Accepted
- **Date:** 2026-11-03

## Context

The author's notes come from work on access-controlled biobank data. That data, its results, and the infrastructure around it cannot be published. Examples still need to be concrete to be useful.

## Decision

- When an example needs data, it uses **public resources**: 1000 Genomes, HapMap, public GWAS summary statistics (e.g., the GWAS Catalog), PharmGKB/CPIC, and tool tutorials.
- When an example does not need data, it **stands alone**: a small snippet, a toy table, or a worked number.
- The book contains **no** private cohort results, internal file paths, cluster hostnames, project codes, account names, or people's names. Institutional resources are described only through their public documentation.

## Alternatives considered

- **A single fictional cohort across the book:** consistent, but simulated results can be mistaken for real findings and add little over public data.
- **Real examples with details removed:** easy to get wrong; one leaked path or count is enough.

## Consequences

- Readers can reproduce data-based examples.
- Every PR is checked for private details (see the PR template).
