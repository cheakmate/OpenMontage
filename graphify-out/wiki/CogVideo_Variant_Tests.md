# CogVideo Variant Tests

> 97 nodes · cohesion 0.04

## Key Concepts

- **probe_output()** (42 connections) — `tools/video/_shared.py`
- **_shared.py** (40 connections) — `tools/video/_shared.py`
- **CogVideoVideo** (21 connections) — `tools/video/cogvideo_video.py`
- **cogvideo_video.py** (20 connections) — `tools/video/cogvideo_video.py`
- **SeedanceVideo** (19 connections) — `tools/video/seedance_video.py`
- **hunyuan_video.py** (19 connections) — `tools/video/hunyuan_video.py`
- **ltx_video_local.py** (19 connections) — `tools/video/ltx_video_local.py`
- **GeminiOmniFalVideo** (18 connections) — `tools/video/gemini_omni_fal.py`
- **KlingVideo** (16 connections) — `tools/video/kling_video.py`
- **SeedanceReplicate** (16 connections) — `tools/video/seedance_replicate.py`
- **HeyGenVideo** (15 connections) — `tools/video/heygen_video.py`
- **HunyuanVideo** (15 connections) — `tools/video/hunyuan_video.py`
- **LTXVideoLocal** (15 connections) — `tools/video/ltx_video_local.py`
- **LTXVideoModal** (15 connections) — `tools/video/ltx_video_modal.py`
- **test_cogvideo_i2v_variant.py** (13 connections) — `tests/tools/test_cogvideo_i2v_variant.py`
- **generate_local_video()** (12 connections) — `tools/video/_shared.py`
- **local_generation_status()** (11 connections) — `tools/video/_shared.py`
- **upload_image_fal()** (11 connections) — `tools/video/_shared.py`
- **.execute()** (7 connections) — `tools/video/gemini_omni_fal.py`
- **.execute()** (7 connections) — `tools/video/seedance_video.py`
- **estimate_local_runtime()** (7 connections) — `tools/video/_shared.py`
- **generate_heygen_video()** (7 connections) — `tools/video/_shared.py`
- **test_execute_allows_i2v_for_5b_variant()** (6 connections) — `tests/tools/test_cogvideo_i2v_variant.py`
- **.execute()** (6 connections) — `tools/video/heygen_video.py`
- **.execute()** (6 connections) — `tools/video/kling_video.py`
- *... and 72 more nodes in this community*

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (168 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (28 shared connections)
- [Kling Client Tests](Kling_Client_Tests.md) (6 shared connections)
- [Video Model Provider Tests](Video_Model_Provider_Tests.md) (5 shared connections)
- [MPS Device Tests](MPS_Device_Tests.md) (4 shared connections)
- [Kling LipSync Implementation](Kling_LipSync_Implementation.md) (2 shared connections)
- [Grok Media Tools](Grok_Media_Tools.md) (2 shared connections)
- [Provider Model Defaults](Provider_Model_Defaults.md) (2 shared connections)
- [Environment Loader](Environment_Loader.md) (2 shared connections)
- [Veo Video Tests](Veo_Video_Tests.md) (2 shared connections)
- [Segment Cost Planning Tests](Segment_Cost_Planning_Tests.md) (1 shared connections)
- [Kling Avatar LipSync Tests](Kling_Avatar_LipSync_Tests.md) (1 shared connections)

## Source Files

- `tests/tools/test_cogvideo_i2v_variant.py`
- `tools/video/_shared.py`
- `tools/video/cogvideo_video.py`
- `tools/video/gemini_omni_fal.py`
- `tools/video/heygen_video.py`
- `tools/video/hunyuan_video.py`
- `tools/video/kling_video.py`
- `tools/video/ltx_video_local.py`
- `tools/video/ltx_video_modal.py`
- `tools/video/seedance_replicate.py`
- `tools/video/seedance_video.py`

## Audit Trail

- EXTRACTED: 319 (79%)
- INFERRED: 86 (21%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*