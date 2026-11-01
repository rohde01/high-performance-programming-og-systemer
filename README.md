# High Performance Programming og systemer

University of Copenhagen · BSc Computer Science and Economics · Autumn 2023, block 2 · 7.5 ECTS  
Course code NDAB20001U · [Course description](https://kurser.ku.dk/course/ndab20001u)

Programming for performance in C, covering memory hierarchies, data layout, parallelism and how hardware and the operating system shape running time. The repo has my exam report, which benchmarks a naive N-body simulation against a Barnes-Hut variant.

## Contents

| Folder | Contents |
| --- | --- |
| `exam/` | My exam report, `main.tex` and `main.pdf` |

## Topics

- N-body simulation
- Barnes-Hut

## Tools

C, LaTeX

## Build

Each LaTeX source sits next to its PDF. Rebuild a PDF from its folder with:

```bash
tectonic -Z continue-on-errors main.tex
```
