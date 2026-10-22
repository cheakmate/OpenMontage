# Scene Detection

> 14 nodes · cohesion 0.18

## Key Concepts

- **.execute()** (8 connections) — `tools/analysis/scene_detect.py`
- **._detect_ffmpeg()** (7 connections) — `tools/analysis/scene_detect.py`
- **._escape_lavfi_movie_path()** (5 connections) — `tools/analysis/scene_detect.py`
- **SceneDetectEscapingTests** (4 connections) — `tests/tools/test_scene_detect_lavfi_escape.py`
- **._detect_ffmpeg_simple()** (4 connections) — `tools/analysis/scene_detect.py`
- **._detect_pyscenedetect()** (4 connections) — `tools/analysis/scene_detect.py`
- **Any** (3 connections)
- **.test_lavfi_movie_path_escapes_filtergraph_metacharacters()** (2 connections) — `tests/tools/test_scene_detect_lavfi_escape.py`
- **.test_lavfi_movie_path_rejects_single_quote_fail_closed()** (2 connections) — `tests/tools/test_scene_detect_lavfi_escape.py`
- **._has_pyscenedetect()** (2 connections) — `tools/analysis/scene_detect.py`
- **Use PySceneDetect for scene detection.** (1 connections) — `tools/analysis/scene_detect.py`
- **Escape a path for FFmpeg lavfi movie=... without allowing filter injection.** (1 connections) — `tools/analysis/scene_detect.py`
- **Fallback: use FFmpeg scene change filter.** (1 connections) — `tools/analysis/scene_detect.py`
- **Simplest fallback: split into uniform segments.** (1 connections) — `tools/analysis/scene_detect.py`

## Relationships

- [Enhancement Error Tests](Enhancement_Error_Tests.md) (9 shared connections)
- [Video Review Tooling](Video_Review_Tooling.md) (2 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (1 shared connections)
- [Tool Status Reporting](Tool_Status_Reporting.md) (1 shared connections)

## Source Files

- `tests/tools/test_scene_detect_lavfi_escape.py`
- `tools/analysis/scene_detect.py`

## Audit Trail

- EXTRACTED: 26 (90%)
- INFERRED: 3 (10%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*