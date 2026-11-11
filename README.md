# Mathematics Notes

This repository contains the my notes for several mathematics courses. 

The list of notes currently includes:

- Mathematical Studies Analysis
- Introduction to Functional Analysis
- Probability (Graduate)

The notes are in their corresponding folders, together with practice problems.

## Formatting

Format a TeX file in place with the repository's `latexindent` settings:

```sh
latexindent -m -l -wd path/to/file.tex
```

The `-m` option enables hard wrapping, `-l` loads `.latexindent.yaml`, and
`-wd` overwrites the file only when formatting changes it. Run the command from
the repository root so `latexindent` can find the local settings.
