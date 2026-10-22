# Vertical Video Tests

> 12 nodes · cohesion 0.33

## Key Concepts

- **test_video_compose_vertical.py** (13 connections) — `tests/tools/test_video_compose_vertical.py`
- **_dims()** (6 connections) — `tests/tools/test_video_compose_vertical.py`
- **_make_clip()** (6 connections) — `tests/tools/test_video_compose_vertical.py`
- **test_compose_default_is_landscape_hd()** (6 connections) — `tests/tools/test_video_compose_vertical.py`
- **test_compose_target_override_cover()** (6 connections) — `tests/tools/test_video_compose_vertical.py`
- **test_compose_vertical_profile()** (6 connections) — `tests/tools/test_video_compose_vertical.py`
- **_edit_decisions()** (5 connections) — `tests/tools/test_video_compose_vertical.py`
- **Path** (3 connections)
- **Vertical / arbitrary-resolution support for video_compose's FFmpeg compose.…** (1 connections) — `tests/tools/test_video_compose_vertical.py`
- **No profile / no target → unchanged 1920x1080 default (backward compatible).** (1 connections) — `tests/tools/test_video_compose_vertical.py`
- **profile='tiktok' → 1080x1920 (the bug: previously stayed 1920x1080).** (1 connections) — `tests/tools/test_video_compose_vertical.py`
- **metadata.compose_target with fit='cover' → exact requested dims, cropped to…** (1 connections) — `tests/tools/test_video_compose_vertical.py`

## Relationships

- [Cinematic Remotion Adapter](Cinematic_Remotion_Adapter.md) (4 shared connections)
- [Environment Loader](Environment_Loader.md) (3 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (3 shared connections)
- [Project Init Validation](Project_Init_Validation.md) (1 shared connections)

## Source Files

- `tests/tools/test_video_compose_vertical.py`

## Audit Trail

- EXTRACTED: 33 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*