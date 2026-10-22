# Workflow Contract Tests

> 18 nodes · cohesion 0.11

## Key Concepts

- **TestContract** (23 connections) — `tests/contracts/test_comfyui_tools.py`
- **test_workflow_exists_and_valid_json()** (2 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_status_unavailable_without_server()** (2 connections) — `tests/contracts/test_comfyui_tools.py`
- **parametrize** (2 connections)
- **.test_comfyui_layer3_skill_exists()** (1 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_cost_is_zero()** (1 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_custom_workflow_requires_output_node()** (1 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_custom_workflow_schema_requires_output_node_contract()** (1 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_get_info_returns_dict()** (1 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_has_agent_skills()** (1 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_has_capabilities()** (1 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_has_fallbacks()** (1 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_has_input_schema()** (1 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_has_required_identity()** (1 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_idempotency_key_fields()** (1 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_inherits_base_tool()** (1 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_runtime_estimate_positive()** (1 connections) — `tests/contracts/test_comfyui_tools.py`
- **Without a running server, status should be UNAVAILABLE.** (1 connections) — `tests/contracts/test_comfyui_tools.py`

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (5 shared connections)
- [ComfyUI Tool Tests](ComfyUI_Tool_Tests.md) (2 shared connections)
- [ComfyUI Video Workflow Tests](ComfyUI_Video_Workflow_Tests.md) (2 shared connections)

## Source Files

- `tests/contracts/test_comfyui_tools.py`

## Audit Trail

- EXTRACTED: 20 (77%)
- INFERRED: 6 (23%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*