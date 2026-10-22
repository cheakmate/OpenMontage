# ComfyUI Video Workflow Tests

> 29 nodes · cohesion 0.15

## Key Concepts

- **ComfyUIVideo** (47 connections) — `tools/video/comfyui_video.py`
- **.execute()** (25 connections) — `tools/video/comfyui_video.py`
- **TestCustomWorkflowContract** (13 connections) — `tests/contracts/test_comfyui_tools.py`
- **Any** (10 connections)
- **._build_i2v()** (8 connections) — `tools/video/comfyui_video.py`
- **._build_t2v()** (6 connections) — `tools/video/comfyui_video.py`
- **.test_video_custom_workflow_uses_caller_output_node_and_provenance()** (5 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_video_default_timeout_is_generous_not_900s()** (5 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_video_passes_timeout_and_resume_prompt_id_through()** (5 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_video_timeout_surfaces_resumable_prompt_id()** (5 connections) — `tests/contracts/test_comfyui_tools.py`
- **._build_partner_t2v()** (5 connections) — `tools/video/comfyui_video.py`
- **.get_info()** (5 connections) — `tools/video/comfyui_video.py`
- **._workflow_provenance()** (5 connections) — `tools/video/comfyui_video.py`
- **test_comfyui_partner_workflows_and_local_h3_metadata()** (4 connections) — `tests/tools/test_new_video_model_support.py`
- **._load_custom_workflow()** (4 connections) — `tools/video/comfyui_video.py`
- **.test_video_resource_profile_does_not_mandate_16gb()** (3 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_custom_workflow_accepts_model_stack_provenance()** (3 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_video_missing_models_are_structured()** (3 connections) — `tests/contracts/test_comfyui_tools.py`
- **.has_node()** (3 connections) — `tools/_comfyui/client.py`
- **.estimate_cost()** (3 connections) — `tools/video/comfyui_video.py`
- **._model_name()** (3 connections) — `tools/video/comfyui_video.py`
- **Path** (3 connections)
- **.estimate_runtime()** (2 connections) — `tools/video/comfyui_video.py`
- **._log_progress()** (2 connections) — `tools/video/comfyui_video.py`
- **fake_generate()** (1 connections) — `tests/contracts/test_comfyui_tools.py`
- *... and 4 more nodes in this community*

## Relationships

- [Workflow Patching](Workflow_Patching.md) (10 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (10 shared connections)
- [ComfyUI Generation Client](ComfyUI_Generation_Client.md) (7 shared connections)
- [ComfyUI Model Status](ComfyUI_Model_Status.md) (7 shared connections)
- [ComfyUI Client Helpers](ComfyUI_Client_Helpers.md) (6 shared connections)
- [ComfyUI Music Tests](ComfyUI_Music_Tests.md) (4 shared connections)
- [ComfyUI Tool Tests](ComfyUI_Tool_Tests.md) (3 shared connections)
- [Three.js Asset Catalog](Three.js_Asset_Catalog.md) (3 shared connections)
- [Provider Contract Tests](Provider_Contract_Tests.md) (2 shared connections)
- [Video Model Provider Tests](Video_Model_Provider_Tests.md) (2 shared connections)
- [Workflow Contract Tests](Workflow_Contract_Tests.md) (2 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (2 shared connections)

## Source Files

- `tests/contracts/test_comfyui_tools.py`
- `tests/tools/test_new_video_model_support.py`
- `tools/_comfyui/client.py`
- `tools/video/comfyui_video.py`

## Audit Trail

- EXTRACTED: 85 (70%)
- INFERRED: 36 (30%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*