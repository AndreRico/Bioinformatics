# ADR 0003 — One book in four parts, built from the author's working notes

- **Status:** Accepted
- **Date:** 2026-11-03

## Context

The source material is a wiki of about 150 pages: concept notes, tool notes, tutorials, book summaries, and meeting notes, written over several years in English and Portuguese. Pages overlap, some are stubs, and the order reflects when they were written, not how a reader learns.

## Decision

Reorganize the material into one book with four parts, following the path of an analysis:

1. **Foundations:** biology and statistics.
2. **Data and Infrastructure:** how data is produced, stored, and computed on.
3. **Genetic Association Studies:** from genotypes to interpreted loci.
4. **Applications:** pharmacogenomics and knowledge graphs.

Meeting notes, administrative pages, and anything specific to one institution's internal operations stay out.

## Alternatives considered

- **Mirror the wiki tree:** faithful to the source, but it reads as a list of notes, not a book.
- **Separate books per topic:** the topics cross-reference each other constantly (LD appears in biology, QC, and fine-mapping).

## Consequences

- Several wiki pages merge into one chapter, and some pages split across chapters.
- Thin topics in the wiki are expanded so every chapter stands on its own.
