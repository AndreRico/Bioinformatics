# Contributing

Thanks for wanting to improve the handbook. Corrections from people who run these analyses every day are what make it better.

## Before you start

- **A big idea or disagreement?** Open a Discussion first. Changing the book's structure calls for a conversation.
- **An error, broken link, or confusing passage?** Open an issue with the "Fix or suggestion" template, or go straight to a PR.
- **Writing a chapter or section?** Open an issue with the "Chapter or section" template and say you'll take it.

## The flow

1. Every change starts from an issue (except typo fixes).
2. Create a short branch from `main`: `12-saige-chapter`.
3. Run `quarto preview` and check the result in your browser.
4. Open the PR and fill in the template. Write `Closes #12` so the issue closes on merge.
5. CI renders the book and checks the links. Only green CI gets merged.
6. After the merge, the book is published to GitHub Pages automatically.

## Commit messages

We use [Conventional Commits](https://www.conventionalcommits.org/), with the chapter as the scope:

```
docs(ch-11): explain genomic inflation
fix(ch-09): correct the heterozygosity threshold example
ci: add link checking
chore: bump the Quarto version
```

## Writing style

- **Plain English**, direct, in the second person ("you").
- **Lead every section with the conclusion.** The why comes after.
- **Short sentences**, ideally under 25 words.
- **Concrete examples**: a command, a file excerpt, a worked number. Examples that need data use **public resources** (1000 Genomes, HapMap, public summary statistics, PharmGKB). Everything else stays generic.
- **No private or internal data.** No cohort-specific results, internal paths, cluster hostnames, project codes, or people's names. Describe institutional resources only through what their public documentation says.
- **Established technical terms** (GWAS, MAF, LD) are used as is; the first time one appears, explain it and add it to the glossary (Appendix D).
- **Diagrams in Mermaid**, inside the `.qmd` itself, so they are reviewed as text.
- **Formulas in LaTeX** (`$...$`), kept to what the reader needs to interpret results.

## Decisions

Changes to the book's structure, tooling, or license become an ADR in `adr/`. Use `adr/0000-template.md`.
