# Tool Contract Testing

> 23 nodes · cohesion 0.09

## Key Concepts

- **TestContract** (28 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_lazy_imports_requests()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_dashscope_layer3_skill_exists()** (1 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_dry_run_returns_dict()** (1 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_estimate_cost_returns_float()** (1 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_execution_mode()** (1 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_get_info_returns_dict()** (1 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_has_agent_skills()** (1 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_has_capabilities()** (1 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_has_fallbacks()** (1 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_has_input_schema()** (1 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_has_install_instructions()** (1 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_has_required_identity()** (1 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_has_resource_profile()** (1 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_has_retry_policy()** (1 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_has_side_effects()** (1 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_has_user_visible_verification()** (1 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_idempotency_key_fields()** (1 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_inherits_base_tool()** (1 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_status_available_with_key()** (1 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_status_unavailable_without_key()** (1 connections) — `tests/contracts/test_dashscope_tools.py`
- **parametrize** (1 connections)
- **Tool module must not import requests at top level (registry discovery must stay…** (1 connections) — `tests/contracts/test_dashscope_tools.py`

## Relationships

- [Tool Testing](Tool_Testing.md) (2 shared connections)
- [Core Utilities](Core_Utilities.md) (2 shared connections)
- [Tool Execution](Tool_Execution.md) (1 shared connections)
- [DashScope API Testing](DashScope_API_Testing.md) (1 shared connections)
- [Piper TTS Fallback](Piper_TTS_Fallback.md) (1 shared connections)

## Source Files

- `tests/contracts/test_dashscope_tools.py`

## Audit Trail

- EXTRACTED: 23 (79%)
- INFERRED: 6 (21%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*