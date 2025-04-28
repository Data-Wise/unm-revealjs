# Unm-revealjs Extension For Quarto

This extension provides a custom `revealjs` theme specifically tailored for creating University of New Mexico (UNM) branded presentations. It incorporates UNM colors, logos, and typographic styles to create professional, university-aligned slide decks.

Description: This extension is a custom `revealjs` theme for the University of New Mexico. The extension uses colors and logos from the University of New Mexico.

## Installing

Install the extension by running the following command:

```bash
quarto add Data-Wise/unm-revealjs
```

This will install the extension under the `_extensions` subdirectory.
If you're using version control, you will want to check in this directory.

## Using

To use the UNM RevealJS theme in your Quarto presentation, specify the format and theme in your document YAML header:

```yaml
format: 
  unm-revealjs:
    slide-number: c/t
    # logo: "images/ms.png"
    chalkboard:
      theme: chalkboard
```

If additional options are available (e.g., logo placement, color variants), please refer to the examples provided.

## Example

You can find minimal usage examples here:
- [Minimal Example](example.qmd)
- [Extended Example](example-long.qmd)

## Reference

This Quarto extension is inspired by [quarto-revealjs-clean](https://github.com/grantmcdermott/quarto-revealjs-clean) by Grant McDermott, adapted for the University of New Mexico branding guidelines.

## License

This project is licensed under the terms of the [MIT License](LICENSE).

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to open an issue or submit a pull request.

## Acknowledgements

Special thanks to the Quarto community and the developers of `quarto-revealjs-clean` for providing excellent resources and inspiration.
