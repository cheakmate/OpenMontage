# Grok Video Quality Tests

> 17 nodes · cohesion 0.23

## Key Concepts

- **grok_video.py** (23 connections) — `tools/video/grok_video.py`
- **GrokVideo** (21 connections) — `tools/video/grok_video.py`
- **._build_payload()** (6 connections) — `tools/video/grok_video.py`
- **.execute()** (6 connections) — `tools/video/grok_video.py`
- **_file_to_data_uri()** (5 connections) — `tools/video/grok_video.py`
- **.estimate_cost()** (5 connections) — `tools/video/grok_video.py`
- **test_grok_video_quality_score.py** (5 connections) — `tests/tools/test_grok_video_quality_score.py`
- **Any** (5 connections)
- **._input_image_count()** (3 connections) — `tools/video/grok_video.py`
- **._normalize_resolution()** (3 connections) — `tools/video/grok_video.py`
- **_normalize_media_ref()** (3 connections) — `tools/video/grok_video.py`
- **test_grok_video_has_quality_score()** (2 connections) — `tests/tools/test_grok_video_quality_score.py`
- **test_quality_score_surfaces_in_tool_info()** (2 connections) — `tests/tools/test_grok_video_quality_score.py`
- **.estimate_runtime()** (2 connections) — `tools/video/grok_video.py`
- **.get_status()** (2 connections) — `tools/video/grok_video.py`
- **Regression for grok_video quality_score (REVIEW §8 #6). Every premium video…** (1 connections) — `tests/tools/test_grok_video_quality_score.py`
- **xAI Grok Imagine video generation with native synchronized audio. Generates…** (1 connections) — `tools/video/grok_video.py`

## Relationships

- [Tool Testing](Tool_Testing.md) (13 shared connections)
- [Core Utilities](Core_Utilities.md) (12 shared connections)
- [Tool Execution](Tool_Execution.md) (3 shared connections)
- [Character Animation](Character_Animation.md) (3 shared connections)
- [Atlas Provider Tests](Atlas_Provider_Tests.md) (2 shared connections)

## Source Files

- `tests/tools/test_grok_video_quality_score.py`
- `tools/video/grok_video.py`

## Audit Trail

- EXTRACTED: 54 (84%)
- INFERRED: 10 (16%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*