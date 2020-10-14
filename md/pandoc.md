# Pandoc

## Exemplo

Conversão de Markdown para PDF:

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

Referência:
* [Markdown &amp; Pandoc - YouTube](http://youtube.com/watch?v=zFCiY9Sy%20dtI)
