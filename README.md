# Bioinformatics Handbook

An open book on **bioinformatics for human genetics**: from molecular biology and statistics to biobank-scale genetic association studies, pharmacogenomics, and knowledge graphs.

It is a structured version of years of working notes, organized so that each chapter answers one practical question, with Mermaid diagrams, commands, and checklists.

📖 **Read online:** <https://andrerico.github.io/Bioinformatics/>

## What's inside

| Part | Topics |
| --- | --- |
| I — Foundations | Molecular biology, genetic variation, statistics for describing data, statistical inference |
| II — Data and Infrastructure | Lab and sequencing methods, file formats, computing environment (HPC, cloud), biobanks |
| III — Genetic Association Studies | Genotype QC, relatedness and population structure, GWAS, SAIGE, rare variants, meta-analysis, post-GWAS |
| IV — Applications | Pharmacogenomics, knowledge graphs |
| Appendices | Cheat sheets, templates, reading path, glossary |

Examples that need data use **public resources** (1000 Genomes, public summary statistics, PharmGKB). No data, results, or infrastructure details from private cohorts appear in the book.

## Running it locally

1. Install [Quarto](https://quarto.org/docs/get-started/) (version 1.5 or newer).
2. From the repository folder:

   ```bash
   quarto preview
   ```

3. The book opens in your browser and reloads every time you save a file.

To build the final version into `_book/`, run `quarto render`.

## Contributing

- **Conversation, opinions, disagreement:** open a Discussion.
- **A specific error or suggestion:** open an issue with the "Fix or suggestion" template.
- **New text or a correction:** open a PR. The guide is in [CONTRIBUTING.md](CONTRIBUTING.md).

## License

- Book text: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Copy and adapt freely, with attribution.
- Code and configuration examples: [MIT](LICENSE-CODE).

Details in [LICENSE.md](LICENSE.md).

## Disclaimer

This book is for education and research. It is not medical advice, and nothing in it should be used to make clinical decisions.
