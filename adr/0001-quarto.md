# ADR 0001 — The book is written in Quarto and published on GitHub Pages

- **Status:** Accepted
- **Date:** 2026-11-03

## Context

The notes behind this book lived in a wiki. A wiki is easy to write in but hard to review, version, and publish as one coherent text. The book needs Markdown, Git history, pull-request review, a website, formulas, and diagrams that are text (Mermaid).

## Decision

Use [Quarto](https://quarto.org/) in `book` mode, published automatically to GitHub Pages by a GitHub Actions workflow on every merge to `main`. This is the same setup as the author's [SaaS Handbook](https://github.com/Garon-Sys/saas-handbook).

## Alternatives considered

- **Keep the wiki:** no review flow, no public site, and formatting that does not travel.
- **MkDocs Material:** excellent documentation search, but no book-style parts, appendices, or PDF without plugins.
- **Jupyter Book:** strong for executable notebooks, but the book's examples are shell and R snippets that run on large private data, so execution at build time is not useful.

## Consequences

- One source can later produce HTML, PDF, and EPUB. Only HTML is enabled for now.
- LaTeX formulas and Mermaid diagrams render natively.
- Code blocks are illustrative and are not executed at build time.
