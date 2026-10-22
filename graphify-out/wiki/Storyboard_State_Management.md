# Storyboard State Management

> 37 nodes · cohesion 0.10

## Key Concepts

- **state.py** (33 connections) — `backlot/state.py`
- **Path** (16 connections)
- **summarize_project()** (10 connections) — `backlot/state.py`
- **_read_json()** (9 connections) — `backlot/state.py`
- **_build_storyboard()** (8 connections) — `backlot/state.py`
- **_rel()** (7 connections) — `backlot/state.py`
- **_asset_entry()** (6 connections) — `backlot/state.py`
- **_collect_artifacts()** (6 connections) — `backlot/state.py`
- **_collect_history()** (6 connections) — `backlot/state.py`
- **_resolve_artifact()** (6 connections) — `backlot/state.py`
- **_collect_checkpoints()** (5 connections) — `backlot/state.py`
- **_find_poster()** (5 connections) — `backlot/state.py`
- **_find_scene_snapshot()** (5 connections) — `backlot/state.py`
- **_load_pipeline_meta()** (5 connections) — `backlot/state.py`
- **_scan_media()** (5 connections) — `backlot/state.py`
- **Any** (5 connections)
- **_last_activity()** (4 connections) — `backlot/state.py`
- **_resolve_asset_path()** (4 connections) — `backlot/state.py`
- **_find_script_section()** (3 connections) — `backlot/state.py`
- **scene_key()** (1 connections) — `backlot/state.py`
- **BoardState derivation — turn a project directory into renderable state.…** (1 connections) — `backlot/state.py`
- **Current checkpoint per stage (raw dicts, unvalidated by design).** (1 connections) — `backlot/state.py`
- **Archived checkpoint versions per stage (oldest first).** (1 connections) — `backlot/state.py`
- **Artifacts from artifacts/*.json, backfilled from checkpoint payloads.** (1 connections) — `backlot/state.py`
- **Manifest paths appear in several real-world flavors — try them all. Observed on…** (1 connections) — `backlot/state.py`
- *... and 12 more nodes in this community*

## Relationships

- [Backlot Board State](Backlot_Board_State.md) (21 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (4 shared connections)
- [Event Logging](Event_Logging.md) (4 shared connections)
- [Board Server Pages](Board_Server_Pages.md) (3 shared connections)
- [Atelier Project Scaffolding](Atelier_Project_Scaffolding.md) (2 shared connections)
- [Pipeline Loader](Pipeline_Loader.md) (2 shared connections)
- [Pipeline Gate Tests](Pipeline_Gate_Tests.md) (1 shared connections)
- [Backlot Storyboard Server](Backlot_Storyboard_Server.md) (1 shared connections)

## Source Files

- `backlot/state.py`

## Audit Trail

- EXTRACTED: 102 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*