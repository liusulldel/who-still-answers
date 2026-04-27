# Who Still Answers

This repository contains the manuscript materials for the working paper
*Private AI, Public Answer Work, and Certification at Stack Overflow*.

The project studies how Stack Overflow answer work changed during the period
when private AI tools became a more realistic alternative for technical problem
solving. The main question is not only whether activity fell, but which
questions still reached the public archive, who answered them, and how often
early answers became accepted public resolutions.

## What is included

| File | Description |
| --- | --- |
| `01_Manuscript.pdf` | Rendered main manuscript |
| `02_Online_Appendix.pdf` | Appendix with methods, robustness checks, and additional results |
| `source/manuscript.md` | Markdown source for the manuscript |
| `source/online_appendix.md` | Markdown source for the appendix |

There is no build pipeline in this repository. The checked-in PDFs are the
reviewable versions, and the Markdown files are included for transparency. Some
intermediate artifact names are documented in the appendix, but executable
replication code and derived panels are not included in this public package.

## Data

The analysis uses the official Stack Exchange Data Dump for Stack Overflow,
snapshot `2025Q4`, hosted by the Internet Archive:
<https://archive.org/details/stackexchange>.

The raw dump and derived parquet, CSV, or SQLite files are not included here.
They are large, publicly hosted elsewhere, and remain subject to Stack
Exchange's CC BY-SA terms. The appendix documents focal tags, time windows, and
sample construction rules, but this repository should be treated as a manuscript
package rather than a clean-machine replication bundle.

## Scope and caveats

The paper is an observational study of Stack Overflow behavior from
2020-01-01 through 2025-12-31. It compares domains where early generative AI was
more or less plausible as a substitute for asking public questions. The results
should be read as evidence about platform-level reallocation and certification
patterns, not as a direct measure of private AI use by individual users.

## Citation

If you reference this work, please cite:

```bibtex
@unpublished{liu_who_still_answers_2026,
  author = {Liu, Sully},
  title  = {Private AI, Public Answer Work, and Certification at
            Stack Overflow},
  note   = {Working paper},
  year   = {2026}
}
```

## License

The author's original text is released under the MIT License (see `LICENSE`).
Figures, tables, and excerpts derived from Stack Exchange content may inherit
Stack Exchange / Internet Archive CC BY-SA terms and should be reused with
source attribution.
