# Remotion Staging Tests

> 19 nodes · cohesion 0.18

## Key Concepts

- **test_remotion_staging_lifecycle.py** (15 connections) — `tests/tools/test_remotion_staging_lifecycle.py`
- **_inputs()** (6 connections) — `tests/tools/test_remotion_staging_lifecycle.py`
- **_mp4()** (6 connections) — `tests/tools/test_remotion_staging_lifecycle.py`
- **test_pre_render_failure_still_cleans_staged_media()** (6 connections) — `tests/tools/test_remotion_staging_lifecycle.py`
- **render()** (5 connections) — `tests/tools/test_remotion_staging_lifecycle.py`
- **test_public_dir_is_unique_per_render()** (5 connections) — `tests/tools/test_remotion_staging_lifecycle.py`
- **_staging_dirs()** (4 connections) — `tests/tools/test_remotion_staging_lifecycle.py`
- **test_cleanup_leaves_preexisting_dirs_alone()** (4 connections) — `tests/tools/test_remotion_staging_lifecycle.py`
- **test_staged_media_cleaned_up_after_render()** (4 connections) — `tests/tools/test_remotion_staging_lifecycle.py`
- **Path** (3 connections)
- **_public_dir_arg()** (2 connections) — `tests/tools/test_remotion_staging_lifecycle.py`
- **fake_run()** (1 connections) — `tests/tools/test_remotion_staging_lifecycle.py`
- **exploding_open()** (1 connections) — `tests/tools/test_remotion_staging_lifecycle.py`
- **fixture** (1 connections)
- **Lifecycle guarantees for the Remotion render-scoped public dir. Two defects…** (1 connections) — `tests/tools/test_remotion_staging_lifecycle.py`
- **A dir matching the old stem-only name is not ours to delete.** (1 connections) — `tests/tools/test_remotion_staging_lifecycle.py`
- **Drive _remotion_render with the Remotion CLI stubbed out. Returns (tool, calls)…** (1 connections) — `tests/tools/test_remotion_staging_lifecycle.py`
- **Two renders of the same output must not share a staging dir.** (1 connections) — `tests/tools/test_remotion_staging_lifecycle.py`
- **The regression: failure *after* staging but *before* the render. Staging…** (1 connections) — `tests/tools/test_remotion_staging_lifecycle.py`

## Relationships

- [Core Utilities](Core_Utilities.md) (3 shared connections)
- [Video Composition](Video_Composition.md) (2 shared connections)
- [Project Init](Project_Init.md) (1 shared connections)

## Source Files

- `tests/tools/test_remotion_staging_lifecycle.py`

## Audit Trail

- EXTRACTED: 34 (92%)
- INFERRED: 3 (8%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*