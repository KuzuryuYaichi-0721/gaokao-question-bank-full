# GaokaoCoach Full Question Bank

**6,265 questions. Public, CC BY 4.0.**

This is the full normalized question bank used by GaokaoCoach after removing
synthetic demo/test rows and blank stems.

## Files

- `questions.split.json` — 6,265 questions
- `manifest.json` — counts, sources, SHA-256
- `RIGHTS.md` — rights-holder assertion
- `DATA_LICENSE.md` — CC BY 4.0
- `LICENSE` — license pointer

## Coverage

- Beijing 2016–2026: 高考/一模/二模
- GAOKAO-Bench 2016–2022
- GAOKAO-Bench-Updates 2023–2024
- selected Xiaohongshu items

## Fields

```text
id paper_key paper_title subject region year month exam_era exam_type
exam_kind mock_level mock_no mock_scope district section q_no type q_type
stem options answer explanation material source source_url license
answer_basis answer_confidence tags marks mark_note status
```

## Markers

```text
【画线】……【/画线】
【波浪线】……【/波浪线】
【加点】……【/加点】
```

`mark_note` records items where the original PDF formatting could not be
located in the text layer. No span is guessed.

## Quality

- OCR-derived Beijing 2021–2026 rows are C-confidence.
- Some answers are empty; empty does not mean the answer is intentionally blank.
- 30 OCR choice rows may lack options.
- Original PDFs/images are not included.

## License

Data: CC BY 4.0, attribution `KuzuryuYaichi-0721 / GaokaoCoach`.
See `RIGHTS.md` for the repository owner's rights assertion and takedown path.
