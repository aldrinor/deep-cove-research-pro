# Data

[`deep-cove-research-pro.jsonl`](deep-cove-research-pro.jsonl) holds the 100 reports in the official DeepResearch Bench format: one JSON object per line, UTF-8.

| Field | Type | Content |
|:--|:--|:--|
| `id` | integer | Task number, 1–100. Tasks 1–50 are Chinese, 51–100 English. |
| `prompt` | string | The benchmark task, unchanged. |
| `article` | string | The report text, with numbered citation markers and a numbered reference list at the end. |

- Lines: 100, in `id` order.
- Size: 13,250,383 bytes.
- SHA-256: `d6bf3c0d09751301a61371dddf965d9eeb4b7f16290e81e923e623b5e11146b3`

A readable page for every report is in [`reports/`](../reports/README.md).
