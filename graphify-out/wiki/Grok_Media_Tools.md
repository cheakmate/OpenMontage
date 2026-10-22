# Grok Media Tools

> 32 nodes · cohesion 0.11

## Key Concepts

- **grok_video.py** (23 connections) — `tools/video/grok_video.py`
- **GrokVideo** (21 connections) — `tools/video/grok_video.py`
- **GrokImage** (18 connections) — `tools/graphics/grok_image.py`
- **mimetypes** (15 connections)
- **.execute()** (7 connections) — `tools/graphics/grok_image.py`
- **._build_payload()** (6 connections) — `tools/video/grok_video.py`
- **.execute()** (6 connections) — `tools/video/grok_video.py`
- **_file_to_data_uri()** (5 connections) — `tools/graphics/grok_image.py`
- **._build_payload()** (5 connections) — `tools/graphics/grok_image.py`
- **_file_to_data_uri()** (5 connections) — `tools/video/grok_video.py`
- **.estimate_cost()** (5 connections) — `tools/video/grok_video.py`
- **test_grok_video_quality_score.py** (5 connections) — `tests/tools/test_grok_video_quality_score.py`
- **Any** (5 connections)
- **.estimate_cost()** (4 connections) — `tools/graphics/grok_image.py`
- **Any** (4 connections)
- **._input_image_count()** (3 connections) — `tools/graphics/grok_image.py`
- **._output_paths()** (3 connections) — `tools/graphics/grok_image.py`
- **_normalize_image_input()** (3 connections) — `tools/graphics/grok_image.py`
- **_media_type()** (3 connections) — `tools/video/atlas_video.py`
- **._input_image_count()** (3 connections) — `tools/video/grok_video.py`
- **._normalize_resolution()** (3 connections) — `tools/video/grok_video.py`
- **_normalize_media_ref()** (3 connections) — `tools/video/grok_video.py`
- **test_grok_video_has_quality_score()** (2 connections) — `tests/tools/test_grok_video_quality_score.py`
- **test_quality_score_surfaces_in_tool_info()** (2 connections) — `tests/tools/test_grok_video_quality_score.py`
- **.get_status()** (2 connections) — `tools/graphics/grok_image.py`
- *... and 7 more nodes in this community*

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (45 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (5 shared connections)
- [TTS Provider Tests](TTS_Provider_Tests.md) (5 shared connections)
- [Kling Client Tests](Kling_Client_Tests.md) (2 shared connections)
- [CogVideo Variant Tests](CogVideo_Variant_Tests.md) (2 shared connections)
- [Seedance Payload Builder](Seedance_Payload_Builder.md) (1 shared connections)

## Source Files

- `tests/tools/test_grok_video_quality_score.py`
- `tools/_kling/media.py`
- `tools/graphics/grok_image.py`
- `tools/video/atlas_video.py`
- `tools/video/grok_video.py`

## Audit Trail

- EXTRACTED: 97 (84%)
- INFERRED: 19 (16%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*