# Posit Quarto PDF Extension

Quarto extension for a template to generate a PDF with Posit-branded LaTeX styling.

## Installation and use

To install the Quarto extension, create a directory, and use the template file:

``` bash
quarto use template posit-marketing/posit-quarto-pdf
```

To use the extension in an existing project without installing the template file:

``` bash
quarto install extension posit-marketing/posit-quarto-pdf
```
Note that you will need to update the output format in the YAML of your Quarto document to `format: PositQuarto-pdf` to enable use of the extension:

```
---
title: "Title"
format: PositQuarto-pdf
---
```

## Acknowledgements

This template was made possible thanks to [Nicola Rennie](https://nrennie.rbind.io/) and her blog post, [Making Pretty PDFs with Quarto](https://nrennie.rbind.io/blog/making-pretty-pdf-quarto/).
