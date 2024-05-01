# Pencils and Erasers, on DNA

Journal club presentation on the paper ["Genome-wide programmable transcriptional memory by CRISPR-based epigenome editing"](https://www.cell.com/cell/fulltext/S0092-8674(21)00353-6#%20) by James K. Nuñez, et al. (2021).

## Compiling

Install [Quarto](https://quarto.org/), then run:

```bash
# bundles everything into a single HTML file
quarto render presentation.qmd -M embed-resources:true

# generates a PDF file (requires node.js)
npx decktape presentation.html presentation.pdf
```

## Precompiled files

[PDF version](./presentation.pdf)
[Single HTML file (download first)](./presentation.html)
[Hosted HTML site](https://blob.yumechi.jp/pub/BMEN6374/presentation/presentation.html)
