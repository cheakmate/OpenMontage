# Workflow Testing

> 22 nodes · cohesion 0.15

## Key Concepts

- **ComfyUIImage** (31 connections) — `tools/graphics/comfyui_image.py`
- **.execute()** (17 connections) — `tools/graphics/comfyui_image.py`
- **.load_workflow()** (12 connections) — `tools/_comfyui/client.py`
- **.patch_workflow()** (10 connections) — `tools/_comfyui/client.py`
- **Any** (7 connections)
- **._workflow_provenance()** (5 connections) — `tools/graphics/comfyui_image.py`
- **.test_image_custom_workflow_uses_caller_output_node_and_provenance()** (4 connections) — `tests/contracts/test_comfyui_tools.py`
- **._load_custom_workflow()** (4 connections) — `tools/graphics/comfyui_image.py`
- **.test_patch_workflow()** (3 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_bundled_workflow_provenance_records_hash_and_stack()** (3 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_image_missing_models_are_structured()** (3 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_image_and_video_tools_use_independent_servers()** (3 connections) — `tests/contracts/test_comfyui_tools.py`
- **.get_info()** (3 connections) — `tools/graphics/comfyui_image.py`
- **._model_name()** (3 connections) — `tools/graphics/comfyui_image.py`
- **.test_load_workflow()** (2 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_patch_workflow_bad_node()** (2 connections) — `tests/contracts/test_comfyui_tools.py`
- **.estimate_cost()** (2 connections) — `tools/graphics/comfyui_image.py`
- **.estimate_runtime()** (2 connections) — `tools/graphics/comfyui_image.py`
- **.__init__()** (2 connections) — `tools/graphics/comfyui_image.py`
- **Any** (1 connections)
- **Load a workflow JSON template from disk.** (1 connections) — `tools/_comfyui/client.py`
- **Deep-copy *workflow* and apply *patches*. *patches* maps ``node_id`` →…** (1 connections) — `tools/_comfyui/client.py`

## Relationships

- [SaveAudio Tests](SaveAudio_Tests.md) (11 shared connections)
- [Custom Workflow](Custom_Workflow.md) (10 shared connections)
- [Tool Testing](Tool_Testing.md) (8 shared connections)
- [Core Utilities](Core_Utilities.md) (4 shared connections)
- [ComfyUI Tool Interface](ComfyUI_Tool_Interface.md) (4 shared connections)
- [ComfyUI Music](ComfyUI_Music.md) (4 shared connections)
- [ComfyUI Model Tests](ComfyUI_Model_Tests.md) (3 shared connections)
- [Tool Registry](Tool_Registry.md) (2 shared connections)
- [Character Animation](Character_Animation.md) (2 shared connections)
- [ComfyUI Tests](ComfyUI_Tests.md) (1 shared connections)
- [Tool Execution](Tool_Execution.md) (1 shared connections)
- [Image Selector](Image_Selector.md) (1 shared connections)

## Source Files

- `tests/contracts/test_comfyui_tools.py`
- `tools/_comfyui/client.py`
- `tools/graphics/comfyui_image.py`

## Audit Trail

- EXTRACTED: 64 (74%)
- INFERRED: 22 (26%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*