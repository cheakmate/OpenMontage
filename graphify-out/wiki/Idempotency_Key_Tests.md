# Idempotency Key Tests

> 12 nodes · cohesion 0.17

## Key Concepts

- **TestDashscopeIdempotencyKeys** (15 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_asr_idempotency_differs_on_enable_words()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_asr_idempotency_differs_on_language_hints()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_asr_idempotency_includes_enable_words_and_language_hints()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_image_idempotency_differs_on_negative_prompt()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_image_idempotency_differs_on_prompt_extend()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_image_idempotency_differs_on_seed()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_image_idempotency_differs_on_watermark()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_image_idempotency_includes_all_output_fields()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_tts_idempotency_differs_on_instructions()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_tts_idempotency_includes_instructions()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **Regression tests for PR #240 review: idempotency keys must include all output-…** (1 connections) — `tests/contracts/test_dashscope_tools.py`

## Relationships

- [DashScope Image Payload](DashScope_Image_Payload.md) (6 shared connections)
- [DashScope ASR Tests](DashScope_ASR_Tests.md) (4 shared connections)
- [DashScope TTS Tests](DashScope_TTS_Tests.md) (3 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (1 shared connections)

## Source Files

- `tests/contracts/test_dashscope_tools.py`

## Audit Trail

- EXTRACTED: 22 (88%)
- INFERRED: 3 (12%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*