# Measurement of Thermal Energy: Form Three Revision Notes

Student revision notes for the Form Three physics topic **"Measurement of Thermal Energy"**, typeset with LaTeX.

## What this is

A print-ready A4 portrait, two-column revision handout that students can read and write alongside. It is original study material, not a verbatim copy of any textbook. It covers the whole topic and includes:

- Restated definitions, NB call-outs, and explanations in student-friendly wording (boxed for quick revision).
- Worked examples solved step-by-step with properly formatted equations.
- Key diagrams redrawn in TikZ.
- An original set of practice questions.
- A full worked-solutions section at the end.

## Files

- `thermal-energy-notes.tex`: the LaTeX source.
- `thermal-energy-notes.pdf`: the compiled output (built from the source).

The `thermal-energy-notes.aux` and `thermal-energy-notes.log` files are build intermediates produced by `pdflatex`; they are not part of the deliverable and can be safely deleted or regenerated.

## Building the PDF

**Prerequisites:** a TeX Live installation providing `pdflatex` (this project was built with TeX Live 2021), with these packages available:
`tikz`/`pgf`, `amsmath`, `siunitx`, `mhchem`, `tcolorbox`, `multicol`, `enumitem`, `xcolor`, and `geometry`.

**Build command** (run twice so TikZ diagrams and cross-references resolve correctly):

```sh
pdflatex -interaction=nonstopmode thermal-energy-notes.tex
pdflatex -interaction=nonstopmode thermal-energy-notes.tex
```

Running from the repository directory produces (or refreshes) `thermal-energy-notes.pdf`.
