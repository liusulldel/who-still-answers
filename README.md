# Private AI, Public Answer Work, and Certification at Stack Overflow

This repository hosts the manuscript and source materials for the working paper
*Private AI, Public Answer Work, and Certification at Stack Overflow* (also
referenced internally as the "Who Still Answers" project).

## Abstract

Private AI creates a new outside option for technical problem solving. Its
effects on public knowledge platforms may therefore appear less in activity
counts than in which questions still reach the public archive, who performs
visible answer work inside that residual queue, and how that work becomes
certified public resolution.

We analyze the official Stack Overflow `2025Q4` dump: 2,035,885
single-focal-tag questions and 2,391,883 matched answers across 16 technical
domains from 2020-01-01 to 2025-12-31. The design compares domains where early
GenAI was a more plausible substitute. We find reallocation inside a
residualized public queue, not just decline. In more exposed domains, the
remaining public questions become more context-heavy and less
exposure-heavy. Within that queue, recent entrants become more visible in
first-answer and early-endorsement roles than in accepted-answer certification
roles. A certification-conversion ladder shows that first answers,
first-positive answers, and top-scored answers are less likely to become
accepted within the first week or month in more exposed domains after the
transition. Tag-months with larger early-versus-accepted composition gaps
exhibit slower endorsed resolution and weaker accepted-answer outcomes. In a
strict question-side AI-ban timing test around 2022-12-05, accepted-window
certification weakens more clearly than immediate answer arrival. External and
direct-AI validation layers are consistent with this interpretation.

The central implication is that private AI can leave a public platform active
while residualizing the public queue, thinning incumbent answer capacity,
reallocating visible answer work toward earlier roles, and weakening the link
between early response and later public certification.

**Keywords:** generative AI; Stack Overflow; online knowledge communities;
digital platforms; contributor composition; public answer supply; certification.

## Contents

| File | Description |
| --- | --- |
| `01_Manuscript.pdf` | Main manuscript (rendered) |
| `02_Online_Appendix.pdf` | Online appendix with extended results, robustness, and methods |
| `03_Cover_Letter.pdf` | Cover letter accompanying journal submission |
| `source/manuscript.md` | Markdown source for the main manuscript |
| `source/online_appendix.md` | Markdown source for the online appendix |
| `source/cover_letter.md` | Markdown source for the cover letter |

## Data availability

All empirical analysis uses the official Stack Exchange Data Dump
(Stack Overflow), `2025Q4` snapshot, distributed by the Internet Archive under
Stack Exchange's CC BY-SA license. The dump is publicly available at
<https://archive.org/details/stackexchange>. We do **not** redistribute the raw
dump (parquet/CSV/SQLite extracts) in this repository because (i) it is large,
(ii) it is already canonically hosted, and (iii) redistribution would impose
attribution and share-alike obligations on downstream users that are simpler to
discharge by going to the canonical source.

The full set of focal-tag domains, time windows, and construction rules needed
to reproduce the analysis sample from the public dump is documented in
`02_Online_Appendix.pdf`.

## How to cite

If you reference this work, please cite the manuscript as:

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

The text and figures in this repository are released under the MIT License
(see `LICENSE`). The underlying Stack Exchange data referenced in the analysis
remains subject to its original CC BY-SA license from Stack Exchange / the
Internet Archive.
