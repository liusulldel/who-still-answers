# Who Still Answers

This repository contains the manuscript materials for
*Private AI, Public Answer Work, and Certification at Stack Overflow*.

Included files:

- `01_Manuscript.pdf` - rendered main manuscript
- `02_Online_Appendix.pdf` - appendix with methods, robustness checks, and additional results
- `source/manuscript.md` - markdown source for the manuscript
- `source/online_appendix.md` - markdown source for the appendix

The repository does not include replication code or derived data. The analysis
uses the official Stack Overflow `2025Q4` data dump, hosted by the Internet
Archive at <https://archive.org/details/stackexchange>. Raw dump extracts and
derived parquet, CSV, or SQLite files are not checked in.

The paper is an observational study of Stack Overflow behavior from
2020-01-01 through 2025-12-31. It compares domains where early generative AI
was more or less plausible as a substitute for asking public questions.

## Headline Panel Statistics

- **N = 2,322,009** focal-tag Stack Overflow questions (full extended panel)
- **N = 2,035,885** focal-tag Stack Overflow questions (harmonized integration cut)
- 16 technical domains; time window 2020-01-01 through 2025-12-31

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
