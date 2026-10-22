# Board State

> 29 nodes · cohesion 0.15

## Key Concepts

- **load_board_state()** (32 connections) — `backlot/state.py`
- **test_state.py** (17 connections) — `tests/backlot/test_state.py`
- **_make_project()** (14 connections) — `tests/backlot/test_state.py`
- **_write()** (13 connections) — `tests/backlot/test_state.py`
- **list_projects()** (9 connections) — `backlot/state.py`
- **TestBoardState** (6 connections) — `tests/backlot/test_state.py`
- **TestFindingsFixes** (6 connections) — `tests/backlot/test_state.py`
- **TestLibrary** (4 connections) — `tests/backlot/test_state.py`
- **.test_full_project()** (4 connections) — `tests/backlot/test_state.py`
- **.test_gate_skip_detection()** (4 connections) — `tests/backlot/test_state.py`
- **.test_generating_state_from_events()** (4 connections) — `tests/backlot/test_state.py`
- **.test_undeclared_stage_surfaces()** (4 connections) — `tests/backlot/test_state.py`
- **.test_artifact_refs_outside_project_are_not_followed()** (4 connections) — `tests/backlot/test_state.py`
- **.test_fresh_in_progress_not_stalled()** (4 connections) — `tests/backlot/test_state.py`
- **.test_inside_project_absolute_refs_still_resolve()** (4 connections) — `tests/backlot/test_state.py`
- **.test_stalled_in_progress_stage_flagged()** (4 connections) — `tests/backlot/test_state.py`
- **.test_list_projects_sorts_live_first()** (4 connections) — `tests/backlot/test_state.py`
- **.test_summary_shape()** (4 connections) — `tests/backlot/test_state.py`
- **_build_stage_rail()** (3 connections) — `backlot/state.py`
- **.test_underscore_dirs_skipped()** (3 connections) — `tests/backlot/test_state.py`
- **projects_root()** (2 connections) — `tests/backlot/test_state.py`
- **.test_degraded_project_never_crashes()** (2 connections) — `tests/backlot/test_state.py`
- **Path** (2 connections)
- **fixture** (1 connections)
- **One entry per manifest stage with derived status + gate audit.** (1 connections) — `backlot/state.py`
- *... and 4 more nodes in this community*

## Relationships

- [Pipeline State](Pipeline_State.md) (21 shared connections)
- [Storyboard Visual Selection Tests](Storyboard_Visual_Selection_Tests.md) (4 shared connections)
- [Server API](Server_API.md) (3 shared connections)
- [Gate Scenario Tests](Gate_Scenario_Tests.md) (3 shared connections)
- [Core Utilities](Core_Utilities.md) (2 shared connections)
- [Event Stream](Event_Stream.md) (1 shared connections)
- [Tool Testing](Tool_Testing.md) (1 shared connections)
- [Project Init](Project_Init.md) (1 shared connections)
- [Backlot Project Management](Backlot_Project_Management.md) (1 shared connections)

## Source Files

- `backlot/state.py`
- `tests/backlot/test_state.py`

## Audit Trail

- EXTRACTED: 97 (99%)
- INFERRED: 1 (1%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*