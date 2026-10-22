# Backlot Project Management

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

- [Core Utilities](Core_Utilities.md) (3 shared connections)
- [Server API](Server_API.md) (2 shared connections)
- [Backlot CLI](Backlot_CLI.md) (1 shared connections)
- [Gate Scenario Tests](Gate_Scenario_Tests.md) (1 shared connections)
- [Board State](Board_State.md) (1 shared connections)
- [Tool Testing](Tool_Testing.md) (1 shared connections)
- [Project Init](Project_Init.md) (1 shared connections)
- [Visual Evaluation System](Visual_Evaluation_System.md) (1 shared connections)
- [Pipeline State](Pipeline_State.md) (1 shared connections)

## Source Files

- `backlot/__init__.py`
- `tests/backlot/test_server.py`

## Audit Trail

- EXTRACTED: 52 (98%)
- INFERRED: 1 (2%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*