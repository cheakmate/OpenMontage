# DashScope API Testing

> 27 nodes · cohesion 0.15

## Key Concepts

- **DashscopeImage** (40 connections) — `tools/graphics/dashscope_image.py`
- **TestDashscopeIdempotencyKeys** (15 connections) — `tests/contracts/test_dashscope_tools.py`
- **TestDashscopeImageSpecific** (11 connections) — `tests/contracts/test_dashscope_tools.py`
- **.execute()** (8 connections) — `tools/graphics/dashscope_image.py`
- **._build_payload()** (7 connections) — `tools/graphics/dashscope_image.py`
- **.estimate_cost()** (5 connections) — `tools/graphics/dashscope_image.py`
- **._safe_error()** (4 connections) — `tools/graphics/dashscope_image.py`
- **Any** (4 connections)
- **.test_build_payload_includes_messages_structure()** (3 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_build_payload_omits_negative_prompt_when_absent()** (3 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_build_payload_optional_negative_prompt()** (3 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_build_payload_uses_asterisk_size()** (3 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_cost_positive_for_image()** (3 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_cost_scales_with_n()** (3 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_default_size_uses_asterisk_format()** (3 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_asr_idempotency_includes_enable_words_and_language_hints()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_image_idempotency_differs_on_negative_prompt()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_image_idempotency_differs_on_prompt_extend()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_image_idempotency_differs_on_seed()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_image_idempotency_differs_on_watermark()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_image_idempotency_includes_all_output_fields()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_default_model_is_qwen_image_2_pro()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_safe_error_redacts_key()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.get_status()** (2 connections) — `tools/graphics/dashscope_image.py`
- **Exception** (1 connections)
- *... and 2 more nodes in this community*

## Relationships

- [Tool Testing](Tool_Testing.md) (8 shared connections)
- [Multi-Output Testing](Multi-Output_Testing.md) (7 shared connections)
- [DashScope ASR](DashScope_ASR.md) (4 shared connections)
- [Core Utilities](Core_Utilities.md) (4 shared connections)
- [Piper TTS Fallback](Piper_TTS_Fallback.md) (3 shared connections)
- [Dashscope Registry Tests](Dashscope_Registry_Tests.md) (2 shared connections)
- [Tool Execution](Tool_Execution.md) (2 shared connections)
- [Character Animation](Character_Animation.md) (2 shared connections)
- [Image Download Tests](Image_Download_Tests.md) (1 shared connections)
- [Tool Contract Testing](Tool_Contract_Testing.md) (1 shared connections)

## Source Files

- `tests/contracts/test_dashscope_tools.py`
- `tools/graphics/dashscope_image.py`

## Audit Trail

- EXTRACTED: 63 (74%)
- INFERRED: 22 (26%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*