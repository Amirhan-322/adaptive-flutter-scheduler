# Thesis documents

**Development and Experimental Evaluation of a Self-Adaptive Computational Task
Scheduling System for Cross-Platform Flutter Applications**

Author: Amir Aminov

Supervisor: Mahmoud Naderi

| File | Contents |
| --- | --- |
| [thesis_title.docx](thesis_title.docx) | Title page in the university's Word template. |
| [research_proposal.pdf](research_proposal.pdf) | Research proposal. |
| [chapters.pdf](chapters.pdf) | Introduction, literature review and references in English. |
| [chapters.tex](chapters.tex) | Standalone LaTeX source for the chapters. |

The chapters PDF includes the title page. Its editable Word version is also
provided separately. The LaTeX source builds the chapters without the title page.

## Building the chapters

Use pdfLaTeX. With TeX Live or MiKTeX and `latexmk` installed, run from this folder:

```sh
latexmk -pdf chapters.tex
```

Alternatively, upload `chapters.tex` to Overleaf and select **pdfLaTeX** as the
compiler. The bibliography is embedded in the source; no separate `.bib` file is
required.
