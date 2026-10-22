# Image Selector Tests

> 40 nodes · cohesion 0.10

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
- **test_image_selector_maps_shared_reference_input()** (6 connections) — `tests/tools/test_hunyuan_image.py`
- **.test_image_selector_custom_workflow_requires_output_node()** (5 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_image_selector_passes_degraded_tool_for_custom_workflow()** (5 connections) — `tests/contracts/test_comfyui_tools.py`
- **.estimate_cost()** (5 connections) — `tools/graphics/image_selector.py`
- **._prepare_task_context()** (5 connections) — `tools/graphics/image_selector.py`
- **._tool_context_payload()** (5 connections) — `tools/graphics/image_selector.py`
- **test_image_selector_maps_model_name_to_google_model()** (4 connections) — `tests/tools/test_google_imagen_gemini_backend.py`
- **._has_custom_workflow()** (4 connections) — `tools/graphics/image_selector.py`
- **._serialize_rankings()** (4 connections) — `tools/graphics/image_selector.py`
- **.fallback_tools()** (3 connections) — `tools/graphics/image_selector.py`
- **.provider_matrix()** (3 connections) — `tools/graphics/image_selector.py`
- **.test_selector_schemas_expose_custom_workflow_inputs()** (3 connections) — `tests/contracts/test_comfyui_tools.py`
- *... and 15 more nodes in this community*

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (24 shared connections)
- [Comfy Video Selector](Comfy_Video_Selector.md) (8 shared connections)
- [Provider Contract Tests](Provider_Contract_Tests.md) (5 shared connections)
- [Seedream Image Tests](Seedream_Image_Tests.md) (4 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (4 shared connections)
- [ComfyUI Tool Tests](ComfyUI_Tool_Tests.md) (3 shared connections)
- [MiniMax Image Tests](MiniMax_Image_Tests.md) (3 shared connections)
- [Hunyuan Image Tests](Hunyuan_Image_Tests.md) (3 shared connections)
- [Provider Scoring](Provider_Scoring.md) (3 shared connections)
- [Lyria BGM Generator](Lyria_BGM_Generator.md) (2 shared connections)
- [Atlas Image Routes](Atlas_Image_Routes.md) (2 shared connections)
- [Imagen Gemini Backend](Imagen_Gemini_Backend.md) (2 shared connections)

## Source Files

- `tests/contracts/test_comfyui_tools.py`
- `tests/contracts/test_phase2_contracts.py`
- `tests/tools/test_google_imagen_gemini_backend.py`
- `tests/tools/test_hunyuan_image.py`
- `tests/tools/test_provider_refresh.py`
- `tools/base_tool.py`
- `tools/graphics/image_selector.py`
- `tools/schema_media.py`

## Audit Trail

- EXTRACTED: 131 (80%)
- INFERRED: 32 (20%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*