# Video Tool Readiness

> 26 nodes · cohesion 0.10

## Key Concepts

- **._filter_candidates()** (14 connections) — `tools/video/video_selector.py`
- **._select_best_tool()** (10 connections) — `tools/video/video_selector.py`
- **_DegradedComfyVideo** (9 connections) — `tests/contracts/test_comfyui_tools.py`
- **TestVideoOperationReadiness** (8 connections) — `tests/contracts/test_comfyui_tools.py`
- **._tool_selectable()** (8 connections) — `tools/video/video_selector.py`
- **._custom_workflow_eligible()** (7 connections) — `tools/video/video_selector.py`
- **.test_video_selector_rank_uses_target_operation_for_readiness()** (6 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_video_selector_custom_workflow_requires_output_node()** (5 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_video_selector_passes_degraded_tool_for_custom_workflow()** (5 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_video_selector_filters_operation_unready_tools()** (5 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_video_selector_custom_workflow_needs_server()** (4 connections) — `tests/contracts/test_comfyui_tools.py`
- **._has_custom_workflow()** (3 connections) — `tools/video/video_selector.py`
- **._operation_ready()** (3 connections) — `tools/video/video_selector.py`
- **.execute()** (1 connections) — `tests/contracts/test_comfyui_tools.py`
- **.get_status()** (1 connections) — `tests/contracts/test_comfyui_tools.py`
- **.is_operation_available()** (1 connections) — `tests/contracts/test_comfyui_tools.py`
- **get_status()** (1 connections) — `tests/contracts/test_comfyui_tools.py`
- **execute()** (1 connections) — `tests/contracts/test_comfyui_tools.py`
- **is_operation_available()** (1 connections) — `tests/contracts/test_comfyui_tools.py`
- **execute()** (1 connections) — `tests/contracts/test_comfyui_tools.py`
- **is_operation_available()** (1 connections) — `tests/contracts/test_comfyui_tools.py`
- **_tool_for()** (1 connections) — `tools/video/video_selector.py`
- **Server reachable, but bundled WAN models missing -> DEGRADED, no operation…** (1 connections) — `tests/contracts/test_comfyui_tools.py`
- **Select the best provider using scored ranking. Respects preferred_provider and…** (1 connections) — `tools/video/video_selector.py`
- **Whether a tool can run the caller-supplied custom workflow. Eligibility is…** (1 connections) — `tools/video/video_selector.py`
- *... and 1 more nodes in this community*

## Relationships

- [Video Selector](Video_Selector.md) (18 shared connections)
- [Core Utilities](Core_Utilities.md) (7 shared connections)
- [Image Selector](Image_Selector.md) (5 shared connections)
- [ComfyUI Tests](ComfyUI_Tests.md) (2 shared connections)
- [Tool Execution](Tool_Execution.md) (2 shared connections)
- [ComfyUI Model Tests](ComfyUI_Model_Tests.md) (1 shared connections)
- [Custom Workflow](Custom_Workflow.md) (1 shared connections)
- [Provider Refresh](Provider_Refresh.md) (1 shared connections)
- [Path Scoring](Path_Scoring.md) (1 shared connections)

## Source Files

- `tests/contracts/test_comfyui_tools.py`
- `tools/video/video_selector.py`

## Audit Trail

- EXTRACTED: 54 (78%)
- INFERRED: 15 (22%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*