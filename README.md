# BRP-ACC531

BRP Acc Fall 2026 - Audit Quality and Earnings Management: Evidence from Textile Composite Companies Listed on the Pakistan Stock Exchange, 2020--2025.

Course ACC531 - Department of Accounting and Finance, IoBM.
Authors: Mustafa Aftab, Ossaid Qadri, Samiya Younus, Alina Shafqat, Airaaf Mehmood. Supervisor: Dr. Asif Bloch.
Researcher iD (Ossaid Qadri): https://orcid.org/0009-0000-1723-803X

## Contents

- `main.tex` - document shell, APA 7 setup (fonts, headings, captions, bib)
- `chapters/` - `ch1.tex` (Introduction), `ch2.tex` (Literature Review), `ch3.tex` (Methodology)
- `appendix.tex` - sampled company tables
- `references.bib` - BibLaTeX database (APA style, biber backend)

The compiled PDF is not tracked; compile it from source.

## Building

Requires LuaLaTeX + Biber (Overleaf: Menu > Compiler > LuaLaTeX), or a full TeX distribution with TeX Gyre Termes fonts installed.

```
lualatex main.tex
biber main
lualatex main.tex
lualatex main.tex
```

Two final passes resolve the table of contents and bibliography. Output: `main.pdf` (~29 pages, APA 7 formatting throughout).

## Status

Chapters 1-3 and the appendix are complete. Chapter 4 (results) and Chapter 5 (conclusion) follow once the panel data analysis in Stata is done.
