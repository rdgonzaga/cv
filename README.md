# CV / Resume

Source files for my resume, written in LaTeX (`main.tex`) and Markdown (`main.md`).

## Overleaf Setup

1. Import this repository into [Overleaf](https://www.overleaf.com/) or upload `main.tex` to a new project.
2. Set `main.tex` as the main document and compile.

## Local Compilation

Build the PDF locally using `pdflatex` or `latexmk`:

```bash
pdflatex main.tex
```

or:

```bash
latexmk -pdf main.tex
```

## Repository Structure

- [`main.tex`](main.tex): Primary LaTeX resume template.
- [`main.md`](main.md): Plain markdown copy of the resume.
- [`.github/workflows/build-pdf.yml`](.github/workflows/build-pdf.yml): Workflow to compile `main.pdf` on push.

## Credits

LaTeX template adapted from [Jake Gutierrez](https://github.com/jakegut/resume).

