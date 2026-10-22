# Character Animation Tests

> 103 nodes · cohesion 0.04

## Key Concepts

- **ToolResult** (540 connections) — `tools/base_tool.py`
- **test_character_animation_pipeline.py** (31 connections) — `tests/contracts/test_character_animation_pipeline.py`
- **character_animation.py** (29 connections) — `tools/character/character_animation.py`
- **cap_recorder.py** (25 connections) — `tools/capture/cap_recorder.py`
- **ImageGen** (18 connections) — `tools/graphics/image_gen.py`
- **CapRecorder** (17 connections) — `tools/capture/cap_recorder.py`
- **PixabayImage** (16 connections) — `tools/graphics/pixabay_image.py`
- **PixabayVideo** (16 connections) — `tools/video/pixabay_video.py`
- **AudioProbe** (14 connections) — `tools/analysis/audio_probe.py`
- **PexelsImage** (14 connections) — `tools/graphics/pexels_image.py`
- **PexelsVideo** (14 connections) — `tools/video/pexels_video.py`
- **CharacterSpecGenerator** (13 connections) — `tools/character/character_animation.py`
- **QwenImage21** (13 connections) — `tools/graphics/qwen_image_21.py`
- **ActionTimelineCompiler** (12 connections) — `tools/character/character_animation.py`
- **CharacterAnimationReviewer** (12 connections) — `tools/character/character_animation.py`
- **CharacterRigRenderer** (12 connections) — `tools/character/character_animation.py`
- **PoseLibraryBuilder** (12 connections) — `tools/character/character_animation.py`
- **SvgRigBuilder** (12 connections) — `tools/character/character_animation.py`
- **test_character_renderer_can_handoff_to_video_compose()** (11 connections) — `tests/contracts/test_character_animation_pipeline.py`
- **test_character_animation_smoke_flow()** (8 connections) — `tests/contracts/test_character_animation_pipeline.py`
- **.execute()** (8 connections) — `tools/capture/cap_recorder.py`
- **_find_cap_recordings_dir()** (8 connections) — `tools/capture/cap_recorder.py`
- **_write_json()** (8 connections) — `tools/character/character_animation.py`
- **.execute()** (8 connections) — `tools/graphics/image_gen.py`
- **Any** (8 connections)
- *... and 78 more nodes in this community*

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (285 shared connections)
- [CogVideo Variant Tests](CogVideo_Variant_Tests.md) (28 shared connections)
- [TTS Provider Tests](TTS_Provider_Tests.md) (24 shared connections)
- [Cinematic Remotion Adapter](Cinematic_Remotion_Adapter.md) (17 shared connections)
- [HyperFrames Render Tests](HyperFrames_Render_Tests.md) (15 shared connections)
- [Base Tool Cache Tests](Base_Tool_Cache_Tests.md) (11 shared connections)
- [Kling Client Tests](Kling_Client_Tests.md) (9 shared connections)
- [Artifact Schema Validation](Artifact_Schema_Validation.md) (9 shared connections)
- [Tool Status Reporting](Tool_Status_Reporting.md) (8 shared connections)
- [Enhancement Error Tests](Enhancement_Error_Tests.md) (8 shared connections)
- [Tool Registry Discovery](Tool_Registry_Discovery.md) (7 shared connections)
- [Audio Mixer Tests](Audio_Mixer_Tests.md) (7 shared connections)

## Source Files

- `tests/contracts/test_character_animation_pipeline.py`
- `tests/tools/test_provider_refresh.py`
- `tools/analysis/audio_probe.py`
- `tools/base_tool.py`
- `tools/capture/cap_recorder.py`
- `tools/character/character_animation.py`
- `tools/enhancement/bg_remove.py`
- `tools/enhancement/face_restore.py`
- `tools/graphics/image_gen.py`
- `tools/graphics/pexels_image.py`
- `tools/graphics/pixabay_image.py`
- `tools/graphics/qwen_image_21.py`
- `tools/video/pexels_video.py`
- `tools/video/pixabay_video.py`
- `tools/video/showcase_card.py`

## Audit Trail

- EXTRACTED: 660 (74%)
- INFERRED: 236 (26%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*