# Event Logging

> 39 nodes · cohesion 0.07

## Key Concepts

- **backlot_simulate_run.py** (15 connections) — `scripts/backlot_simulate_run.py`
- **emit_event()** (14 connections) — `lib/events.py`
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
- **wrapper()** (4 connections) — `tools/base_tool.py`
- **.test_execute_emits_error_event_and_reraises()** (3 connections) — `tests/contracts/test_backlot_contract.py`
- **.test_execute_emits_events()** (3 connections) — `tests/contracts/test_backlot_contract.py`
- **.test_emit_and_read_roundtrip()** (3 connections) — `tests/contracts/test_backlot_contract.py`
- **Any** (3 connections)
- **Path** (3 connections)
- **artifacts_for()** (2 connections) — `scripts/backlot_simulate_run.py`
- **cp()** (2 connections) — `scripts/backlot_simulate_run.py`
- **execute()** (2 connections) — `tests/contracts/test_backlot_contract.py`
- **.test_unattributable_call_emits_nothing_and_works()** (2 connections) — `tests/contracts/test_backlot_contract.py`
- *... and 14 more nodes in this community*

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (24 shared connections)
- [Pipeline Checkpointing](Pipeline_Checkpointing.md) (15 shared connections)
- [Backlot Screenshot Capture](Backlot_Screenshot_Capture.md) (4 shared connections)
- [Storyboard State Management](Storyboard_State_Management.md) (4 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (3 shared connections)
- [Lyria BGM Generator](Lyria_BGM_Generator.md) (3 shared connections)
- [Project Init Validation](Project_Init_Validation.md) (2 shared connections)
- [Idempotency Cache Wrapper](Idempotency_Cache_Wrapper.md) (2 shared connections)
- [Artifact Schema Validation](Artifact_Schema_Validation.md) (2 shared connections)
- [BFL API Client](BFL_API_Client.md) (2 shared connections)
- [Backlot Board State](Backlot_Board_State.md) (1 shared connections)
- [Asset Cache](Asset_Cache.md) (1 shared connections)

## Source Files

- `lib/events.py`
- `lib/paths.py`
- `scripts/backlot_simulate_run.py`
- `tests/contracts/test_backlot_contract.py`
- `tools/base_tool.py`

## Audit Trail

- EXTRACTED: 121 (97%)
- INFERRED: 4 (3%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*