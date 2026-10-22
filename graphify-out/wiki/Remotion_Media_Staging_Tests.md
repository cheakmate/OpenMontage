# Remotion Media Staging Tests

> 18 nodes · cohesion 0.14

## Key Concepts

- **test_remotion_media_staging.py** (12 connections) — `tests/tools/test_remotion_media_staging.py`
- **._mirror_public_dir()** (8 connections) — `tools/video/video_compose.py`
- **._file_uri_to_raw_path()** (5 connections) — `tools/video/video_compose.py`
- **test_file_uri_to_raw_path()** (4 connections) — `tests/tools/test_remotion_media_staging.py`
- **test_mirror_is_read_only_toward_source()** (4 connections) — `tests/tools/test_remotion_media_staging.py`
- **test_mirror_never_clobbers_staged_media()** (4 connections) — `tests/tools/test_remotion_media_staging.py`
- **test_mirror_public_dir_exposes_prestaged_assets()** (4 connections) — `tests/tools/test_remotion_media_staging.py`
- **test_unc_authority_still_treated_as_network_path()** (4 connections) — `tests/tools/test_remotion_media_staging.py`
- **visit()** (4 connections) — `tools/video/video_compose.py`
- **test_mirror_missing_source_is_noop()** (3 connections) — `tests/tools/test_remotion_media_staging.py`
- **parametrize** (1 connections)
- **Regression coverage for Remotion media staging (`_stage_remotion_media`). Two…** (1 connections) — `tests/tools/test_remotion_media_staging.py`
- **Cleanup deletes the staging dir; the real public/ must survive.** (1 connections) — `tests/tools/test_remotion_media_staging.py`
- **A genuine UNC host must not be mistaken for a drive path.** (1 connections) — `tests/tools/test_remotion_media_staging.py`
- **anime_scene.images[] / screenshot_scene.backgroundImage are staticFile() refs…** (1 connections) — `tests/tools/test_remotion_media_staging.py`
- **Staged render media wins over a same-named entry in public/.** (1 connections) — `tests/tools/test_remotion_media_staging.py`
- **Convert a ``file:`` URI to a raw filesystem path string. Handles the forms…** (1 connections) — `tools/video/video_compose.py`
- **Link the real ``public/`` tree into a render-scoped ``--public-dir``.…** (1 connections) — `tools/video/video_compose.py`

## Relationships

- [Cinematic Remotion Adapter](Cinematic_Remotion_Adapter.md) (13 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (2 shared connections)
- [Project Init Validation](Project_Init_Validation.md) (1 shared connections)

## Source Files

- `tests/tools/test_remotion_media_staging.py`
- `tools/video/video_compose.py`

## Audit Trail

- EXTRACTED: 32 (84%)
- INFERRED: 6 (16%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*