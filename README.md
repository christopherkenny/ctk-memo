# ctk-memo Format

The `ctk-memo` Quarto template is a general purpose memo template, designed to aesthetically align with the [`ctk-article` template](https://github.com/christopherkenny/ctk-article).

<!-- pdftools::pdf_convert('template.pdf', pages = 1) -->
![[template.qmd](template.qmd)](template_1.png)

## Installing

```bash
quarto use template christopherkenny/ctk-memo
```

This will install the format extension and create an example qmd file
that you can use as a starting place for your document.

## Using `ctk-memo`

This extension builds your Quarto documents using a Typst backend.
[Typst](https://github.com/typst/typst).

This template is relatively simple.
Some options you can set:

- `title`: A title of the document.
- `authors`: Author names to use. Only names are used, not affiliations.
- `header-left`: A left header, typically a short title
- `header-right`: A right header, typically names or last names


### Fonts

By default, the `ctk-memo` format uses the Spectral font. This can be installed from [Google Fonts](https://fonts.google.com/specimen/Spectral).

To check that it is installed, run:

```
quarto typst fonts
```

If no font by the name "Spectral" is found, it falls back to Crimson Text. This can be installed from [Google Fonts](https://fonts.google.com/specimen/Crimson+Text).

If no font by the names "Spectral", "Crimson Text", or "Crimson" is found, the template falls back to Linux Libertine.

This backup font of Crimson Text is chosen to look like [Cory McCartan's cmc-article](https://github.com/corymccartan/cmc-article) which uses Cochineal.

## License

This template is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
