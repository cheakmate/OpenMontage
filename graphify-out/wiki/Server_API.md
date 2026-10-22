# Server API

> 33 nodes · cohesion 0.09

## Key Concepts

- **server.py** (27 connections) — `backlot/server.py`
- **create_app()** (15 connections) — `backlot/server.py`
- **_lifespan()** (6 connections) — `backlot/server.py`
- **_safe_project_dir()** (6 connections) — `backlot/server.py`
- **_ui_html()** (5 connections) — `backlot/server.py`
- **_watch_projects()** (5 connections) — `backlot/server.py`
- **_sse()** (4 connections) — `backlot/server.py`
- **_thumbnail_for()** (4 connections) — `backlot/server.py`
- **_cached_summaries()** (3 connections) — `backlot/server.py`
- **project_events()** (3 connections) — `backlot/server.py`
- **project_state()** (3 connections) — `backlot/server.py`
- **thumb()** (3 connections) — `backlot/server.py`
- **_project_of_change()** (3 connections) — `backlot/server.py`
- **FastAPI** (3 connections)
- **board_page()** (2 connections) — `backlot/server.py`
- **board_page_path()** (2 connections) — `backlot/server.py`
- **library_events()** (2 connections) — `backlot/server.py`
- **stream()** (2 connections) — `backlot/server.py`
- **library_page()** (2 connections) — `backlot/server.py`
- **stream()** (2 connections) — `backlot/server.py`
- **projects()** (2 connections) — `backlot/server.py`
- **_invalidate_summary()** (2 connections) — `backlot/server.py`
- **Path** (2 connections)
- **health()** (1 connections) — `backlot/server.py`
- **ui_no_cache()** (1 connections) — `backlot/server.py`
- *... and 8 more nodes in this community*

## Relationships

- [Core Utilities](Core_Utilities.md) (4 shared connections)
- [Pipeline State](Pipeline_State.md) (3 shared connections)
- [Board State](Board_State.md) (3 shared connections)
- [Tool Testing](Tool_Testing.md) (3 shared connections)
- [Backlot Project Management](Backlot_Project_Management.md) (2 shared connections)
- [Media Gateway Handler](Media_Gateway_Handler.md) (2 shared connections)
- [Lyria BGM Generation](Lyria_BGM_Generation.md) (2 shared connections)
- [ChangeHub Notifications](ChangeHub_Notifications.md) (1 shared connections)

## Source Files

- `backlot/server.py`

## Audit Trail

- EXTRACTED: 65 (94%)
- INFERRED: 4 (6%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*