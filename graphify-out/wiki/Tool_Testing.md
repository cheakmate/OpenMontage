# Tool Testing

> 158 nodes · cohesion 0.04

## Key Concepts

- **Determinism** (245 connections) — `tools/base_tool.py`
- **ExecutionMode** (244 connections) — `tools/base_tool.py`
- **ToolRuntime** (229 connections) — `tools/base_tool.py`
- **typing** (183 connections)
- **RetryPolicy** (160 connections) — `tools/base_tool.py`
- **time** (144 connections)
- **os** (108 connections)
- **probe_output()** (42 connections) — `tools/video/_shared.py`
- **_shared.py** (40 connections) — `tools/video/_shared.py`
- **comfyui_music.py** (27 connections) — `tools/audio/comfyui_music.py`
- **test_dashscope_tools.py** (26 connections) — `tests/contracts/test_dashscope_tools.py`
- **comfyui_video.py** (26 connections) — `tools/video/comfyui_video.py`
- **comfyui_image.py** (25 connections) — `tools/graphics/comfyui_image.py`
- **wan_video.py** (25 connections) — `tools/video/wan_video.py`
- **fal_3d.py** (24 connections) — `tools/graphics/fal_3d.py`
- **jimeng_video.py** (24 connections) — `tools/video/jimeng_video.py`
- **veo_video.py** (24 connections) — `tools/video/veo_video.py`
- **clip_search.py** (23 connections) — `tools/video/clip_search.py`
- **SeedreamImage** (21 connections) — `tools/graphics/seedream_image.py`
- **audio_energy.py** (20 connections) — `tools/analysis/audio_energy.py`
- **doubao_tts.py** (20 connections) — `tools/audio/doubao_tts.py`
- **cogvideo_video.py** (20 connections) — `tools/video/cogvideo_video.py`
- **heygen_video.py** (20 connections) — `tools/video/heygen_video.py`
- **test_jimeng_video.py** (19 connections) — `tests/contracts/test_jimeng_video.py`
- **azure_tts.py** (19 connections) — `tools/audio/azure_tts.py`
- *... and 133 more nodes in this community*

## Relationships

- [Core Utilities](Core_Utilities.md) (622 shared connections)
- [Tool Execution](Tool_Execution.md) (143 shared connections)
- [Character Animation](Character_Animation.md) (82 shared connections)
- [Kling Tools](Kling_Tools.md) (47 shared connections)
- [Tool Contracts](Tool_Contracts.md) (38 shared connections)
- [Atlas Provider Tests](Atlas_Provider_Tests.md) (36 shared connections)
- [Audio Mixing](Audio_Mixing.md) (30 shared connections)
- [Tool Status Checks](Tool_Status_Checks.md) (27 shared connections)
- [3D Asset Tests](3D_Asset_Tests.md) (22 shared connections)
- [TTS Provider Tests](TTS_Provider_Tests.md) (16 shared connections)
- [Phase Comparison](Phase_Comparison.md) (14 shared connections)
- [Media Source Adapters](Media_Source_Adapters.md) (14 shared connections)

## Source Files

- `tests/contracts/test_dashscope_tools.py`
- `tests/contracts/test_jimeng_video.py`
- `tools/_comfyui/client.py`
- `tools/_comfyui/metadata.py`
- `tools/analysis/audio_energy.py`
- `tools/analysis/dashscope_asr.py`
- `tools/analysis/transcript_fetcher.py`
- `tools/audio/azure_tts.py`
- `tools/audio/comfyui_music.py`
- `tools/audio/dashscope_tts.py`
- `tools/audio/doubao_tts.py`
- `tools/audio/fal_elevenlabs_music.py`
- `tools/audio/fish_audio_tts.py`
- `tools/audio/music_gen.py`
- `tools/audio/openai_tts.py`
- `tools/audio/piper_tts.py`
- `tools/audio/suno_music.py`
- `tools/base_tool.py`
- `tools/capture/screen_capture_selector.py`
- `tools/enhancement/bg_remove.py`

## Audit Trail

- EXTRACTED: 1681 (79%)
- INFERRED: 457 (21%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*