# Lab Notebook

Add a dated entry every time you make a change to this repo. Newest entries at the top.

## 2026-09-23 — Claude Code
- Problem: `analysis/summarize.py` crashed with `KeyError: 'cohort'` on line 14. The script looked up `row["cohort"]`, but the column in `data/reaction_times.csv` is named `group` (header: `subject_id,group,response_time_ms`).
- Fix: changed `row["cohort"]` to `row["group"]` in `load_groups()`.
- Verified: script now runs and prints `control: n=10, mean=504.7 ms` and `treatment: n=10, mean=430.8 ms`.

## Example — 2026-01-01 — A. Researcher
- Ran `analysis/summarize.py` for the first time; confirmed the repo and my tool are connected.
- No changes made yet — just checking the pipeline works end to end.

<!-- Add your own entry above this line -->
