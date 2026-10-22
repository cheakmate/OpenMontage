# Tool Registry Discovery

> 46 nodes · cohesion 0.08

## Key Concepts

- **.discover()** (40 connections) — `tools/tool_registry.py`
- **.get()** (33 connections) — `tools/tool_registry.py`
- **.get_by_capability()** (11 connections) — `tools/tool_registry.py`
- **TestRegistryDiscovery** (8 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **test_video_selector_prefers_official_provider_without_fal_upload()** (7 connections) — `tests/contracts/test_kling_official_video.py`
- **test_image_selector_prefers_official_provider()** (6 connections) — `tests/contracts/test_kling_official_image.py`
- **test_tts_selector_prefers_kling_official()** (6 connections) — `tests/contracts/test_kling_tts.py`
- **test_registry_discovers_music_library()** (6 connections) — `tests/tools/test_music_library.py`
- **.find_by_capability()** (6 connections) — `tools/tool_registry.py`
- **.test_discovers_concrete_tools_from_package()** (5 connections) — `tests/contracts/test_phase0_contracts.py`
- **.test_all_phase1_tools_discoverable()** (5 connections) — `tests/contracts/test_phase1_contracts.py`
- **.test_registry_discovers_tool()** (5 connections) — `tests/contracts/test_wan_video.py`
- **test_registry_discovers_export_bundle()** (5 connections) — `tests/tools/test_export_bundle.py`
- **test_registry_discovers_provider()** (5 connections) — `tests/tools/test_fal_elevenlabs_music.py`
- **test_registry_discovers_fal_tts()** (5 connections) — `tests/tools/test_fal_elevenlabs_tts.py`
- **test_threejs_world_contract_and_registry_discovery()** (5 connections) — `tests/tools/test_threejs_world.py`
- **TestDiscovery** (4 connections) — `tests/tools/test_azure_stt.py`
- **TestDiscovery** (4 connections) — `tests/tools/test_azure_tts.py`
- **.test_all_phase2_tools_discoverable()** (4 connections) — `tests/contracts/test_phase2_contracts.py`
- **test_registry_discovers_separate_3d_capabilities()** (4 connections) — `tests/tools/test_3d_asset_generation.py`
- **.test_capability_routing()** (4 connections) — `tests/tools/test_azure_stt.py`
- **.test_discoverable()** (4 connections) — `tests/tools/test_azure_stt.py`
- **.test_capability_routing()** (4 connections) — `tests/tools/test_azure_tts.py`
- **.test_discoverable()** (4 connections) — `tests/tools/test_azure_tts.py`
- **test_gemini_omni_is_discovered_as_video_provider()** (4 connections) — `tests/tools/test_gemini_omni_video.py`
- *... and 21 more nodes in this community*

## Relationships

- [Tool Registry Discovery Tests](Tool_Registry_Discovery_Tests.md) (33 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (11 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (7 shared connections)
- [Kling Client Tests](Kling_Client_Tests.md) (6 shared connections)
- [Tool Registry Tests](Tool_Registry_Tests.md) (4 shared connections)
- [Kling Image Provider Tests](Kling_Image_Provider_Tests.md) (3 shared connections)
- [Kling Video Tests](Kling_Video_Tests.md) (3 shared connections)
- [Comfy Video Selector](Comfy_Video_Selector.md) (2 shared connections)
- [Kling Avatar LipSync Tests](Kling_Avatar_LipSync_Tests.md) (2 shared connections)
- [Three.js World Generation](Three.js_World_Generation.md) (2 shared connections)
- [ComfyUI Setup Registry](ComfyUI_Setup_Registry.md) (2 shared connections)
- [Video Model Provider Tests](Video_Model_Provider_Tests.md) (2 shared connections)

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
- `tests/tools/test_3d_asset_generation.py`
- `tests/tools/test_azure_stt.py`
- `tests/tools/test_azure_tts.py`
- `tests/tools/test_export_bundle.py`
- `tests/tools/test_fal_elevenlabs_music.py`
- `tests/tools/test_fal_elevenlabs_tts.py`
- `tests/tools/test_gemini_omni_video.py`
- `tests/tools/test_hunyuan_image.py`
- `tests/tools/test_minimax_video.py`

## Audit Trail

- EXTRACTED: 75 (45%)
- INFERRED: 93 (55%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*