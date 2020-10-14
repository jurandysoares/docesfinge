# Pandoc

## Exemplo

```sh
pandoc --smart \
       --standalone \
       --filter=pandoc-crossref \
       --filter=pandoc-citeproc \
       --latex-engine=pdflatex \
       --table-of-contents \
       --toc-depth=2 \
       --number-sections \
       --listing \
       --from=markdown \
       --to=latex
       --output=markupt.pdf
       markup.md
```
