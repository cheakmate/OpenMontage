# DashScope Image Payload

> 21 nodes · cohesion 0.19

## Key Concepts

- **DashscopeImage** (40 connections) — `tools/graphics/dashscope_image.py`
- **TestDashscopeImageSpecific** (11 connections) — `tests/contracts/test_dashscope_tools.py`
- **.execute()** (8 connections) — `tools/graphics/dashscope_image.py`
- **._build_payload()** (7 connections) — `tools/graphics/dashscope_image.py`
- **.estimate_cost()** (5 connections) — `tools/graphics/dashscope_image.py`
- **.test_image_selector_finds_dashscope()** (4 connections) — `tests/contracts/test_dashscope_tools.py`
- **._safe_error()** (4 connections) — `tools/graphics/dashscope_image.py`
- **Any** (4 connections)
- **.test_build_payload_includes_messages_structure()** (3 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_build_payload_omits_negative_prompt_when_absent()** (3 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_build_payload_optional_negative_prompt()** (3 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_build_payload_uses_asterisk_size()** (3 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_cost_positive_for_image()** (3 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_cost_scales_with_n()** (3 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_default_size_uses_asterisk_format()** (3 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_default_model_is_qwen_image_2_pro()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_safe_error_redacts_key()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.get_status()** (2 connections) — `tools/graphics/dashscope_image.py`
- **Exception** (1 connections)
- **CRITICAL: DashScope uses W*H (asterisk), not WxH.** (1 connections) — `tests/contracts/test_dashscope_tools.py`
- **image_selector should auto-discover dashscope_image by capability.** (1 connections) — `tests/contracts/test_dashscope_tools.py`

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (13 shared connections)
- [DashScope Multi-Output Tests](DashScope_Multi-Output_Tests.md) (7 shared connections)
- [Idempotency Key Tests](Idempotency_Key_Tests.md) (6 shared connections)
- [Tool Registry Discovery Tests](Tool_Registry_Discovery_Tests.md) (2 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (2 shared connections)
- [Image Download Tests](Image_Download_Tests.md) (1 shared connections)
- [DashScope Contract Tests](DashScope_Contract_Tests.md) (1 shared connections)
- [Image Selector Tests](Image_Selector_Tests.md) (1 shared connections)

## Source Files

- `tests/contracts/test_dashscope_tools.py`
- `tools/graphics/dashscope_image.py`

## Audit Trail

- EXTRACTED: 53 (73%)
- INFERRED: 20 (27%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*