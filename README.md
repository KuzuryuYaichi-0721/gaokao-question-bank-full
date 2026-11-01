# GaokaoCoach Full Question Bank (Private)

**This repository is private and is not an open-data release.**

It contains the local full question bank used by GaokaoCoach: **6,470 questions**.

## Why private

The full set mixes sources with different redistribution rights:

- GAOKAO-Bench 2016–2022: Apache-2.0
- GAOKAO-Bench-Updates 2023–2024: no declared license
- Beijing 2016–2020 export: source says local study only
- Beijing OCR batch 2021–2026: source sites did not declare redistribution rights
- Xiaohongshu items: third-party content

Only the Apache-2.0 subset is published at
[KuzuryuYaichi-0721/gaokao-question-bank](https://github.com/KuzuryuYaichi-0721/gaokao-question-bank).

## Files

- `questions.split.json` — 6,470 normalized questions
- `manifest.json` — counts, sources, checksum
- `DATA_LICENSE.md` — private-use boundary
- `README.md`

## Do not redistribute

Do not make this repository public, do not mirror it, and do not redistribute
the data without checking every source's license. The code of GaokaoCoach is
MIT; this question data is not.

## Known quality notes

- 988 OCR-derived questions from the Beijing 2021–2026 batch are C-confidence;
  OCR text may contain errors and answers are mostly empty.
- 899 Beijing 2016–2020 questions have no reliable answer source.
- Open data subset contains 2,996 Apache-2.0 questions from 2016–2022.
