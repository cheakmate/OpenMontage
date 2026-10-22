# Comfy Video Selector

> 45 nodes · cohesion 0.08

## Key Concepts

- **VideoSelector** (60 connections) — `tools/video/video_selector.py`
- **.execute()** (15 connections) — `tools/video/video_selector.py`
- **._filter_candidates()** (14 connections) — `tools/video/video_selector.py`
- **._providers()** (10 connections) — `tools/video/video_selector.py`
- **._select_best_tool()** (10 connections) — `tools/video/video_selector.py`
- **_DegradedComfyVideo** (9 connections) — `tests/contracts/test_comfyui_tools.py`
- **TestVideoOperationReadiness** (8 connections) — `tests/contracts/test_comfyui_tools.py`
- **._tool_selectable()** (8 connections) — `tools/video/video_selector.py`
- **._custom_workflow_eligible()** (7 connections) — `tools/video/video_selector.py`
- **.estimate_cost()** (7 connections) — `tools/video/video_selector.py`
- **.test_video_selector_rank_uses_target_operation_for_readiness()** (6 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_video_selector_custom_workflow_requires_output_node()** (5 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_video_selector_passes_degraded_tool_for_custom_workflow()** (5 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_video_selector_filters_operation_unready_tools()** (5 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_video_selector_routes_to_hunyuan_cloud()** (5 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **test_estimate_cost_uses_selected_provider()** (5 connections) — `tests/tools/test_video_selector_routing.py`
- **test_estimate_runtime_uses_selected_provider()** (5 connections) — `tests/tools/test_video_selector_routing.py`
- **.estimate_runtime()** (5 connections) — `tools/video/video_selector.py`
- **._prepare_task_context()** (5 connections) — `tools/video/video_selector.py`
- **.test_video_selector_custom_workflow_needs_server()** (4 connections) — `tests/contracts/test_comfyui_tools.py`
- **._tool_context_payload()** (4 connections) — `tools/video/video_selector.py`
- **.fallback_tools()** (3 connections) — `tools/video/video_selector.py`
- **.provider_matrix()** (3 connections) — `tools/video/video_selector.py`
- **test_estimate_cost_zero_when_no_providers()** (3 connections) — `tests/tools/test_video_selector_routing.py`
- **.get_status()** (3 connections) — `tools/video/video_selector.py`
- *... and 20 more nodes in this community*

## Relationships

- [Video Selector Routing](Video_Selector_Routing.md) (23 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (21 shared connections)
- [Image Selector Tests](Image_Selector_Tests.md) (8 shared connections)
- [ComfyUI Tool Tests](ComfyUI_Tool_Tests.md) (3 shared connections)
- [MiniMax Video Tests](MiniMax_Video_Tests.md) (3 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (3 shared connections)
- [Provider Scoring](Provider_Scoring.md) (3 shared connections)
- [Lyria BGM Generator](Lyria_BGM_Generator.md) (2 shared connections)
- [Gemini Omni Video Tests](Gemini_Omni_Video_Tests.md) (2 shared connections)
- [Tool Registry Discovery](Tool_Registry_Discovery.md) (2 shared connections)
- [ComfyUI Model Status](ComfyUI_Model_Status.md) (1 shared connections)
- [ComfyUI Video Workflow Tests](ComfyUI_Video_Workflow_Tests.md) (1 shared connections)

## Source Files

- `tests/contracts/test_comfyui_tools.py`
- `tests/contracts/test_hunyuan_cloud_video.py`
- `tests/tools/test_video_selector_routing.py`
- `tools/video/video_selector.py`

## Audit Trail

- EXTRACTED: 130 (82%)
- INFERRED: 29 (18%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*