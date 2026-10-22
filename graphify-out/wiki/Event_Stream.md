# Event Stream

> 51 nodes · cohesion 0.06

## Key Concepts

- **backlot_screenshot_stage.py** (27 connections) — `scripts/backlot_screenshot_stage.py`
- **backlot_simulate_run.py** (15 connections) — `scripts/backlot_simulate_run.py`
- **emit_event()** (14 connections) — `lib/events.py`
- **stage_project()** (14 connections) — `scripts/backlot_screenshot_stage.py`
- **events.py** (14 connections) — `lib/events.py`
- **read_events()** (12 connections) — `lib/events.py`
- **datetime** (12 connections)
- **main()** (11 connections) — `scripts/backlot_simulate_run.py`
- **infer_project_dir()** (9 connections) — `lib/events.py`
- **_cache_execute()** (8 connections) — `tools/base_tool.py`
- **_instrument_execute()** (7 connections) — `tools/base_tool.py`
- **TestBaseToolInstrumentation** (6 connections) — `tests/contracts/test_backlot_contract.py`
- **paths.py** (6 connections) — `lib/paths.py`
- **functools** (6 connections)
- **threading** (6 connections)
- **.__init_subclass__()** (5 connections) — `tools/base_tool.py`
- **TestEvents** (4 connections) — `tests/contracts/test_backlot_contract.py`
- **build_stage()** (4 connections) — `scripts/backlot_screenshot_stage.py`
- **cinematic_frame()** (4 connections) — `scripts/backlot_screenshot_stage.py`
- **wrapper()** (4 connections) — `tools/base_tool.py`
- **.test_execute_emits_error_event_and_reraises()** (3 connections) — `tests/contracts/test_backlot_contract.py`
- **.test_execute_emits_events()** (3 connections) — `tests/contracts/test_backlot_contract.py`
- **.test_emit_and_read_roundtrip()** (3 connections) — `tests/contracts/test_backlot_contract.py`
- **Any** (3 connections)
- **Path** (3 connections)
- *... and 26 more nodes in this community*

## Relationships

- [Core Utilities](Core_Utilities.md) (24 shared connections)
- [Pipeline Checkpoints](Pipeline_Checkpoints.md) (16 shared connections)
- [Project Init](Project_Init.md) (10 shared connections)
- [Tool Testing](Tool_Testing.md) (8 shared connections)
- [Lyria BGM Generation](Lyria_BGM_Generation.md) (5 shared connections)
- [Pipeline State](Pipeline_State.md) (4 shared connections)
- [Character Animation](Character_Animation.md) (3 shared connections)
- [Audio Mixing](Audio_Mixing.md) (3 shared connections)
- [Asset Cache Wrapper](Asset_Cache_Wrapper.md) (3 shared connections)
- [Pipeline Loader](Pipeline_Loader.md) (3 shared connections)
- [UI Bug Bash Tests](UI_Bug_Bash_Tests.md) (2 shared connections)
- [Visual Evaluation System](Visual_Evaluation_System.md) (2 shared connections)

## Source Files

- `lib/events.py`
- `lib/paths.py`
- `scripts/backlot_screenshot_stage.py`
- `scripts/backlot_simulate_run.py`
- `tests/contracts/test_backlot_contract.py`
- `tools/base_tool.py`

## Audit Trail

- EXTRACTED: 163 (98%)
- INFERRED: 4 (2%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*