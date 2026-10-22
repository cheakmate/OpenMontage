# Atlas Tool Tests

> 43 nodes · cohesion 0.08

## Key Concepts

- **.discover()** (40 connections) — `tools/tool_registry.py`
- **.get()** (33 connections) — `tools/tool_registry.py`
- **TestRegistryDiscovery** (8 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **test_video_selector_prefers_official_provider_without_fal_upload()** (7 connections) — `tests/contracts/test_kling_official_video.py`
- **test_tts_selector_prefers_kling_official()** (6 connections) — `tests/contracts/test_kling_tts.py`
- **test_registry_discovers_music_library()** (6 connections) — `tests/tools/test_music_library.py`
- **.find_by_capability()** (6 connections) — `tools/tool_registry.py`
- **TestPhase1ToolDiscovery** (5 connections) — `tests/contracts/test_phase1_contracts.py`
- **.test_discovers_concrete_tools_from_package()** (5 connections) — `tests/contracts/test_phase0_contracts.py`
- **.test_all_phase1_tools_discoverable()** (5 connections) — `tests/contracts/test_phase1_contracts.py`
- **.test_registry_discovers_tool()** (5 connections) — `tests/contracts/test_wan_video.py`
- **test_registry_discovers_export_bundle()** (5 connections) — `tests/tools/test_export_bundle.py`
- **test_registry_discovers_provider()** (5 connections) — `tests/tools/test_fal_elevenlabs_music.py`
- **test_registry_discovers_fal_tts()** (5 connections) — `tests/tools/test_fal_elevenlabs_tts.py`
- **.test_all_phase2_tools_discoverable()** (4 connections) — `tests/contracts/test_phase2_contracts.py`
- **.test_discoverable()** (4 connections) — `tests/tools/test_azure_stt.py`
- **.test_discoverable()** (4 connections) — `tests/tools/test_azure_tts.py`
- **test_gemini_omni_is_discovered_as_video_provider()** (4 connections) — `tests/tools/test_gemini_omni_video.py`
- **test_hunyuan_image_is_discovered_by_registry()** (4 connections) — `tests/tools/test_hunyuan_image.py`
- **test_minimax_video_is_discovered_as_direct_provider()** (4 connections) — `tests/tools/test_minimax_video.py`
- **test_sora_video_is_discovered_as_openai_video_provider()** (4 connections) — `tests/tools/test_sora_video.py`
- **.find_fallback()** (4 connections) — `tools/tool_registry.py`
- **TestPhase2ToolDiscovery** (3 connections) — `tests/contracts/test_phase2_contracts.py`
- **test_registry_discovers_atlas_tools()** (3 connections) — `tests/contracts/test_atlas_tools.py`
- **.test_discoverable()** (3 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- *... and 18 more nodes in this community*

## Relationships

- [Tool Registry](Tool_Registry.md) (38 shared connections)
- [Core Utilities](Core_Utilities.md) (6 shared connections)
- [Character Animation](Character_Animation.md) (5 shared connections)
- [Kling Core Tests](Kling_Core_Tests.md) (3 shared connections)
- [Kling Image Tests](Kling_Image_Tests.md) (3 shared connections)
- [Kling Video Tests](Kling_Video_Tests.md) (3 shared connections)
- [Kling TTS Provider Tests](Kling_TTS_Provider_Tests.md) (3 shared connections)
- [Video Selector](Video_Selector.md) (2 shared connections)
- [Kling Avatar Tests](Kling_Avatar_Tests.md) (2 shared connections)
- [Tool Execution](Tool_Execution.md) (2 shared connections)
- [Video Model Support Tests](Video_Model_Support_Tests.md) (2 shared connections)
- [Tool Testing](Tool_Testing.md) (1 shared connections)

## Source Files

- `tests/contracts/test_atlas_tools.py`
- `tests/contracts/test_hunyuan_cloud_video.py`
- `tests/contracts/test_kling_official_avatar.py`
- `tests/contracts/test_kling_official_core.py`
- `tests/contracts/test_kling_official_image.py`
- `tests/contracts/test_kling_official_video.py`
- `tests/contracts/test_kling_tts.py`
- `tests/contracts/test_phase0_contracts.py`
- `tests/contracts/test_phase1_contracts.py`
- `tests/contracts/test_phase2_contracts.py`
- `tests/contracts/test_wan_video.py`
- `tests/tools/test_azure_stt.py`
- `tests/tools/test_azure_tts.py`
- `tests/tools/test_export_bundle.py`
- `tests/tools/test_fal_elevenlabs_music.py`
- `tests/tools/test_fal_elevenlabs_tts.py`
- `tests/tools/test_gemini_omni_video.py`
- `tests/tools/test_hunyuan_image.py`
- `tests/tools/test_minimax_video.py`
- `tests/tools/test_music_library.py`

## Audit Trail

- EXTRACTED: 66 (44%)
- INFERRED: 85 (56%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*