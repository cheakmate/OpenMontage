# Scene Variation Checker

> 12 nodes · cohesion 0.27

## Key Concepts

- **check_scene_variation()** (9 connections) — `lib/variation_checker.py`
- **test_variation_checker_runs.py** (9 connections) — `tests/lib/test_variation_checker_runs.py`
- **variation_checker.py** (5 connections) — `lib/variation_checker.py`
- **_scenes()** (4 connections) — `tests/lib/test_variation_checker_runs.py`
- **test_non_consecutive_same_size_pairs_do_not_trip_run_check()** (3 connections) — `tests/lib/test_variation_checker_runs.py`
- **test_true_run_of_three_is_flagged()** (3 connections) — `tests/lib/test_variation_checker_runs.py`
- **test_unspecified_shots_do_not_form_a_run()** (3 connections) — `tests/lib/test_variation_checker_runs.py`
- **Any** (1 connections)
- **Scene plan variation checker. Analyzes a scene plan for repetitive patterns…** (1 connections) — `lib/variation_checker.py`
- **Analyze a scene plan for repetitive patterns. Returns: { "score": float (0-5,…** (1 connections) — `lib/variation_checker.py`
- **Regression test for check_scene_variation consecutive-run counting. The…** (1 connections) — `tests/lib/test_variation_checker_runs.py`
- **collections** (1 connections)

## Relationships

- [Video Production Bench Runner](Video_Production_Bench_Runner.md) (2 shared connections)
- [Tool Testing](Tool_Testing.md) (1 shared connections)
- [Lyria BGM Generation](Lyria_BGM_Generation.md) (1 shared connections)
- [Core Utilities](Core_Utilities.md) (1 shared connections)

## Source Files

- `lib/variation_checker.py`
- `tests/lib/test_variation_checker_runs.py`

## Audit Trail

- EXTRACTED: 23 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*