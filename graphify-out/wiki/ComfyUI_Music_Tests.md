# ComfyUI Music Tests

> 34 nodes · cohesion 0.12

## Key Concepts

- **ComfyUIMusic** (39 connections) — `tools/audio/comfyui_music.py`
- **.execute()** (24 connections) — `tools/audio/comfyui_music.py`
- **TestComfyUIMusic** (18 connections) — `tests/contracts/test_comfyui_tools.py`
- **fake_generate()** (10 connections) — `tests/contracts/test_comfyui_tools.py`
- **Any** (7 connections)
- **.test_bundled_generation_patches_tags_lyrics_and_seed()** (5 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_bundled_generation_preserves_seed_zero()** (5 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_passes_timeout_and_resume_prompt_id_through()** (5 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_successful_generation_returns_provenance_and_duration()** (5 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_timeout_surfaces_resumable_prompt_id()** (5 connections) — `tests/contracts/test_comfyui_tools.py`
- **.get_status()** (5 connections) — `tools/audio/comfyui_music.py`
- **._workflow_provenance()** (5 connections) — `tools/audio/comfyui_music.py`
- **.test_bundled_path_requires_no_workflow_json_or_output_node()** (4 connections) — `tests/contracts/test_comfyui_tools.py`
- **._load_custom_workflow()** (4 connections) — `tools/audio/comfyui_music.py`
- **._probe_duration()** (4 connections) — `tools/audio/comfyui_music.py`
- **.test_bundled_missing_models_returns_structured_payload()** (3 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_custom_workflow_without_output_node_errors()** (3 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_get_status_degraded_when_model_missing()** (3 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_unavailable_server_reports_unavailable_reason()** (3 connections) — `tests/contracts/test_comfyui_tools.py`
- **.get_info()** (3 connections) — `tools/audio/comfyui_music.py`
- **._model_name()** (3 connections) — `tools/audio/comfyui_music.py`
- **.test_capability_and_provider()** (2 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_uses_music_capability_env_var_for_multi_server()** (2 connections) — `tests/contracts/test_comfyui_tools.py`
- **.estimate_cost()** (2 connections) — `tools/audio/comfyui_music.py`
- **.estimate_runtime()** (2 connections) — `tools/audio/comfyui_music.py`
- *... and 9 more nodes in this community*

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (12 shared connections)
- [ComfyUI Generation Client](ComfyUI_Generation_Client.md) (4 shared connections)
- [ComfyUI Client Helpers](ComfyUI_Client_Helpers.md) (4 shared connections)
- [Workflow Patching](Workflow_Patching.md) (4 shared connections)
- [ComfyUI Video Workflow Tests](ComfyUI_Video_Workflow_Tests.md) (4 shared connections)
- [ComfyUI Model Status](ComfyUI_Model_Status.md) (4 shared connections)
- [Three.js Asset Catalog](Three.js_Asset_Catalog.md) (3 shared connections)
- [ComfyUI Tool Tests](ComfyUI_Tool_Tests.md) (2 shared connections)
- [ComfyUI Setup Registry](ComfyUI_Setup_Registry.md) (2 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (2 shared connections)
- [Tool Registry Discovery Tests](Tool_Registry_Discovery_Tests.md) (1 shared connections)
- [Image Selector Tests](Image_Selector_Tests.md) (1 shared connections)

## Source Files

- `tests/contracts/test_comfyui_tools.py`
- `tools/audio/comfyui_music.py`

## Audit Trail

- EXTRACTED: 71 (63%)
- INFERRED: 41 (37%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*