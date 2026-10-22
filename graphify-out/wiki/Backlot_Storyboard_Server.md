# Backlot Storyboard Server

> 28 nodes · cohesion 0.11

## Key Concepts

- **test_server.py** (19 connections) — `tests/backlot/test_server.py`
- **_make_project()** (10 connections) — `tests/backlot/test_server.py`
- **TestBacklotServerApi** (7 connections) — `tests/backlot/test_server.py`
- **backlot/__init__.py** (5 connections) — `backlot/__init__.py`
- **client()** (4 connections) — `tests/backlot/test_server.py`
- **_write_json()** (4 connections) — `tests/backlot/test_server.py`
- **_write_png()** (4 connections) — `tests/backlot/test_server.py`
- **TestBacklotPerformanceBudgets** (3 connections) — `tests/backlot/test_server.py`
- **TestFindingsFixes** (3 connections) — `tests/backlot/test_server.py`
- **.test_image_thumb_generation_stays_within_budget()** (3 connections) — `tests/backlot/test_server.py`
- **.test_projects_and_state_stay_within_loose_budgets()** (3 connections) — `tests/backlot/test_server.py`
- **.test_thumb_downscales_image_and_passes_through_non_media()** (3 connections) — `tests/backlot/test_server.py`
- **Path** (3 connections)
- **projects_root()** (2 connections) — `tests/backlot/test_server.py`
- **.test_media_rejects_path_traversal()** (2 connections) — `tests/backlot/test_server.py`
- **.test_media_serves_range_requests()** (2 connections) — `tests/backlot/test_server.py`
- **.test_project_id_rejects_bad_or_unknown_ids()** (2 connections) — `tests/backlot/test_server.py`
- **.test_projects_shape_and_state()** (2 connections) — `tests/backlot/test_server.py`
- **.test_thumb_never_serves_raw_video_bytes()** (2 connections) — `tests/backlot/test_server.py`
- **fixture** (2 connections)
- **io** (2 connections)
- **no_watch()** (1 connections) — `tests/backlot/test_server.py`
- **.test_health()** (1 connections) — `tests/backlot/test_server.py`
- **parametrize** (1 connections)
- **Backlot — the living storyboard. A read-only, disk-derived production board for…** (1 connections) — `backlot/__init__.py`
- *... and 3 more nodes in this community*

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (4 shared connections)
- [Board Server Pages](Board_Server_Pages.md) (2 shared connections)
- [Lyria BGM Generator](Lyria_BGM_Generator.md) (1 shared connections)
- [Pipeline Gate Tests](Pipeline_Gate_Tests.md) (1 shared connections)
- [Backlot Board State](Backlot_Board_State.md) (1 shared connections)
- [Project Init Validation](Project_Init_Validation.md) (1 shared connections)
- [Backlot Visual Eval](Backlot_Visual_Eval.md) (1 shared connections)
- [Storyboard State Management](Storyboard_State_Management.md) (1 shared connections)

## Source Files

- `backlot/__init__.py`
- `tests/backlot/test_server.py`

## Audit Trail

- EXTRACTED: 52 (98%)
- INFERRED: 1 (2%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*