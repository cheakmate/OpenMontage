# ComfyUI Model Status

> 13 nodes · cohesion 0.21

## Key Concepts

- **.check_models()** (9 connections) — `tools/_comfyui/client.py`
- **.is_available()** (9 connections) — `tools/_comfyui/client.py`
- **.operation_statuses()** (8 connections) — `tools/video/comfyui_video.py`
- **.test_video_tool_reports_partial_operation_readiness()** (6 connections) — `tests/contracts/test_comfyui_tools.py`
- **.get_status()** (5 connections) — `tools/video/comfyui_video.py`
- **.get_status()** (4 connections) — `tools/graphics/comfyui_image.py`
- **.list_models()** (3 connections) — `tools/_comfyui/client.py`
- **.is_operation_available()** (3 connections) — `tools/video/comfyui_video.py`
- **fake_check_models()** (1 connections) — `tests/contracts/test_comfyui_tools.py`
- **Query ComfyUI for available models, grouped by type. Returns a dict like:: {…** (1 connections) — `tools/_comfyui/client.py`
- **Check which of *required* model filenames are available. Returns ``(found,…** (1 connections) — `tools/_comfyui/client.py`
- **Return True if the ComfyUI server is reachable.** (1 connections) — `tools/_comfyui/client.py`
- **Return per-operation readiness for selector routing and preflight.** (1 connections) — `tools/video/comfyui_video.py`

## Relationships

- [ComfyUI Video Workflow Tests](ComfyUI_Video_Workflow_Tests.md) (7 shared connections)
- [ComfyUI Music Tests](ComfyUI_Music_Tests.md) (4 shared connections)
- [ComfyUI Client Helpers](ComfyUI_Client_Helpers.md) (3 shared connections)
- [Workflow Patching](Workflow_Patching.md) (3 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (2 shared connections)
- [Comfy Video Selector](Comfy_Video_Selector.md) (1 shared connections)

## Source Files

- `tests/contracts/test_comfyui_tools.py`
- `tools/_comfyui/client.py`
- `tools/graphics/comfyui_image.py`
- `tools/video/comfyui_video.py`

## Audit Trail

- EXTRACTED: 19 (53%)
- INFERRED: 17 (47%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*