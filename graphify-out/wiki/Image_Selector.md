# Image Selector

> 39 nodes · cohesion 0.11

## Key Concepts

- **ImageSelector** (47 connections) — `tools/graphics/image_selector.py`
- **.get_info()** (18 connections) — `tools/base_tool.py`
- **.execute()** (15 connections) — `tools/graphics/image_selector.py`
- **.get_status()** (11 connections) — `tools/base_tool.py`
- **._filter_candidates()** (11 connections) — `tools/graphics/image_selector.py`
- **TestCustomWorkflowSelectorEligibility** (10 connections) — `tests/contracts/test_comfyui_tools.py`
- **._select_best_tool()** (10 connections) — `tools/graphics/image_selector.py`
- **Any** (10 connections)
- **._tool_selectable()** (9 connections) — `tools/graphics/image_selector.py`
- **._custom_workflow_eligible()** (8 connections) — `tools/graphics/image_selector.py`
- **._providers()** (8 connections) — `tools/graphics/image_selector.py`
- **_DegradedComfyImage** (7 connections) — `tests/contracts/test_comfyui_tools.py`
- **test_exact_image_tool_selects_same_host_sibling()** (7 connections) — `tests/tools/test_provider_refresh.py`
- **.test_image_selector_custom_workflow_requires_output_node()** (5 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_image_selector_passes_degraded_tool_for_custom_workflow()** (5 connections) — `tests/contracts/test_comfyui_tools.py`
- **.estimate_cost()** (5 connections) — `tools/graphics/image_selector.py`
- **._prepare_task_context()** (5 connections) — `tools/graphics/image_selector.py`
- **._tool_context_payload()** (5 connections) — `tools/graphics/image_selector.py`
- **test_image_selector_maps_model_name_to_google_model()** (4 connections) — `tests/tools/test_google_imagen_gemini_backend.py`
- **.test_image_selector_routes_count_and_returns_distinct_artifacts()** (4 connections) — `tests/tools/test_seedream_image.py`
- **._has_custom_workflow()** (4 connections) — `tools/graphics/image_selector.py`
- **._serialize_rankings()** (4 connections) — `tools/graphics/image_selector.py`
- **.fallback_tools()** (3 connections) — `tools/graphics/image_selector.py`
- **.provider_matrix()** (3 connections) — `tools/graphics/image_selector.py`
- **.test_selector_schemas_expose_custom_workflow_inputs()** (3 connections) — `tests/contracts/test_comfyui_tools.py`
- *... and 14 more nodes in this community*

## Relationships

- [Core Utilities](Core_Utilities.md) (13 shared connections)
- [Tool Execution](Tool_Execution.md) (6 shared connections)
- [Provider Refresh](Provider_Refresh.md) (6 shared connections)
- [Video Tool Readiness](Video_Tool_Readiness.md) (5 shared connections)
- [Seedream Tests](Seedream_Tests.md) (4 shared connections)
- [ComfyUI Tests](ComfyUI_Tests.md) (3 shared connections)
- [Video Selector](Video_Selector.md) (3 shared connections)
- [TTS Provider Tests](TTS_Provider_Tests.md) (3 shared connections)
- [MiniMax Image](MiniMax_Image.md) (3 shared connections)
- [Phase Comparison](Phase_Comparison.md) (3 shared connections)
- [Path Scoring](Path_Scoring.md) (3 shared connections)
- [Atlas Media Smoke](Atlas_Media_Smoke.md) (2 shared connections)

## Source Files

- `tests/contracts/test_comfyui_tools.py`
- `tests/contracts/test_phase2_contracts.py`
- `tests/tools/test_google_imagen_gemini_backend.py`
- `tests/tools/test_provider_refresh.py`
- `tests/tools/test_seedream_image.py`
- `tools/base_tool.py`
- `tools/graphics/image_selector.py`
- `tools/schema_media.py`

## Audit Trail

- EXTRACTED: 129 (81%)
- INFERRED: 31 (19%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*