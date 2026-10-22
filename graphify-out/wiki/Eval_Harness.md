# Eval Harness

> 27 nodes · cohesion 0.12

## Key Concepts

- **harness.py** (11 connections) — `tests/eval/replay_harness/harness.py`
- **GoldenScenario** (7 connections) — `tests/eval/replay_harness/harness.py`
- **ReplayHarness** (7 connections) — `tests/eval/replay_harness/harness.py`
- **.evaluate()** (7 connections) — `tests/eval/replay_harness/harness.py`
- **.run_all()** (7 connections) — `tests/eval/replay_harness/harness.py`
- **.load_scenarios()** (5 connections) — `tests/eval/replay_harness/harness.py`
- **EvalMode** (4 connections) — `tests/eval/replay_harness/harness.py`
- **EvalResult** (4 connections) — `tests/eval/replay_harness/harness.py`
- **default_comparator()** (4 connections) — `tests/eval/replay_harness/harness.py`
- **.load()** (4 connections) — `tests/eval/replay_harness/harness.py`
- **.register_comparator()** (3 connections) — `tests/eval/replay_harness/harness.py`
- **Any** (3 connections)
- **Path** (3 connections)
- **.save()** (2 connections) — `tests/eval/replay_harness/harness.py`
- **.__init__()** (2 connections) — `tests/eval/replay_harness/harness.py`
- **Enum** (2 connections)
- **Comparator** (1 connections)
- **str** (1 connections)
- **Replay evaluation harness. Provides the scaffold for replaying golden scenarios…** (1 connections) — `tests/eval/replay_harness/harness.py`
- **Load all golden scenarios, optionally filtering by tags.** (1 connections) — `tests/eval/replay_harness/harness.py`
- **Compare actual artifacts against expected for a scenario.** (1 connections) — `tests/eval/replay_harness/harness.py`
- **Run all scenarios through a runner function and evaluate results.** (1 connections) — `tests/eval/replay_harness/harness.py`
- **A known-good input -> output pair for regression testing.** (1 connections) — `tests/eval/replay_harness/harness.py`
- **Result of evaluating a single scenario.** (1 connections) — `tests/eval/replay_harness/harness.py`
- **Default comparator: exact match for deterministic, threshold for stochastic.** (1 connections) — `tests/eval/replay_harness/harness.py`
- *... and 2 more nodes in this community*

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (3 shared connections)
- [Asset Cache Modules](Asset_Cache_Modules.md) (1 shared connections)

## Source Files

- `tests/eval/replay_harness/harness.py`

## Audit Trail

- EXTRACTED: 44 (98%)
- INFERRED: 1 (2%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*