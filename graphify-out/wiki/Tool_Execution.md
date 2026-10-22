# Tool Execution

> 80 nodes · cohesion 0.04

## Key Concepts

- **ToolStatus** (355 connections) — `tools/base_tool.py`
- **corpus_builder.py** (36 connections) — `tools/video/corpus_builder.py`
- **tool_registry.py** (33 connections) — `tools/tool_registry.py`
- **direct_clip_search.py** (32 connections) — `tools/video/direct_clip_search.py`
- **CorpusBuilder** (27 connections) — `tools/video/corpus_builder.py`
- **test_documentary_governance.py** (25 connections) — `tests/tools/test_documentary_governance.py`
- **test_azure_tts.py** (22 connections) — `tests/tools/test_azure_tts.py`
- **DirectClipSearch** (19 connections) — `tools/video/direct_clip_search.py`
- **GeminiOmniFalVideo** (18 connections) — `tools/video/gemini_omni_fal.py`
- **FreesoundMusic** (16 connections) — `tools/audio/freesound_music.py`
- **PixabayImage** (16 connections) — `tools/graphics/pixabay_image.py`
- **PixabayVideo** (16 connections) — `tools/video/pixabay_video.py`
- **SeedanceReplicate** (16 connections) — `tools/video/seedance_replicate.py`
- **LocalDiffusion** (15 connections) — `tools/graphics/local_diffusion.py`
- **LTXVideoModal** (15 connections) — `tools/video/ltx_video_modal.py`
- **AudioProbe** (14 connections) — `tools/analysis/audio_probe.py`
- **BgRemove** (14 connections) — `tools/enhancement/bg_remove.py`
- **PexelsImage** (14 connections) — `tools/graphics/pexels_image.py`
- **ClipSearch** (14 connections) — `tools/video/clip_search.py`
- **PexelsVideo** (14 connections) — `tools/video/pexels_video.py`
- **FaceRestore** (13 connections) — `tools/enhancement/face_restore.py`
- **available_sources()** (10 connections) — `tools/video/stock_sources/__init__.py`
- **.execute()** (7 connections) — `tools/video/gemini_omni_fal.py`
- **test_corpus_builder_reports_source_level_discoverability()** (6 connections) — `tests/tools/test_documentary_governance.py`
- **.execute()** (6 connections) — `tools/video/seedance_replicate.py`
- *... and 55 more nodes in this community*

## Relationships

- [Tool Testing](Tool_Testing.md) (143 shared connections)
- [Core Utilities](Core_Utilities.md) (130 shared connections)
- [Character Animation](Character_Animation.md) (35 shared connections)
- [Streaming Tests](Streaming_Tests.md) (19 shared connections)
- [Tool Contracts](Tool_Contracts.md) (12 shared connections)
- [Stock Source Protocol](Stock_Source_Protocol.md) (12 shared connections)
- [Tool Contract Tests](Tool_Contract_Tests.md) (11 shared connections)
- [3D Asset Tests](3D_Asset_Tests.md) (10 shared connections)
- [TTS Provider Tests](TTS_Provider_Tests.md) (10 shared connections)
- [Atlas Provider Tests](Atlas_Provider_Tests.md) (9 shared connections)
- [Music Library Testing](Music_Library_Testing.md) (8 shared connections)
- [Video Selector](Video_Selector.md) (7 shared connections)

## Source Files

- `tests/tools/test_azure_tts.py`
- `tests/tools/test_documentary_governance.py`
- `tools/analysis/audio_probe.py`
- `tools/audio/freesound_music.py`
- `tools/base_tool.py`
- `tools/enhancement/bg_remove.py`
- `tools/enhancement/face_restore.py`
- `tools/graphics/local_diffusion.py`
- `tools/graphics/openai_image.py`
- `tools/graphics/pexels_image.py`
- `tools/graphics/pixabay_image.py`
- `tools/tool_registry.py`
- `tools/video/clip_search.py`
- `tools/video/corpus_builder.py`
- `tools/video/direct_clip_search.py`
- `tools/video/gemini_omni_fal.py`
- `tools/video/ltx_video_modal.py`
- `tools/video/pexels_video.py`
- `tools/video/pixabay_video.py`
- `tools/video/seedance_replicate.py`

## Audit Trail

- EXTRACTED: 512 (66%)
- INFERRED: 260 (34%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*