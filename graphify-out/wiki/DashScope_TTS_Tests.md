# DashScope TTS Tests

> 20 nodes · cohesion 0.18

## Key Concepts

- **DashscopeTTS** (31 connections) — `tools/audio/dashscope_tts.py`
- **TestDashscopeTtsSpecific** (10 connections) — `tests/contracts/test_dashscope_tools.py`
- **.execute()** (7 connections) — `tools/audio/dashscope_tts.py`
- **._build_payload()** (5 connections) — `tools/audio/dashscope_tts.py`
- **.test_tts_selector_finds_dashscope()** (4 connections) — `tests/contracts/test_dashscope_tools.py`
- **.estimate_cost()** (4 connections) — `tools/audio/dashscope_tts.py`
- **._safe_error()** (4 connections) — `tools/audio/dashscope_tts.py`
- **.test_build_payload_adds_instructions_for_instruct_model()** (3 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_build_payload_includes_input_text_voice()** (3 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_cost_scales_with_text_length()** (3 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_fallback_includes_piper()** (3 connections) — `tests/contracts/test_dashscope_tools.py`
- **Any** (3 connections)
- **.test_default_language_is_auto()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_default_model_is_qwen3_tts_flash()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_default_voice_is_cherry()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_safe_error_redacts_key()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.get_status()** (2 connections) — `tools/audio/dashscope_tts.py`
- **Exception** (1 connections)
- **Piper is the free offline fallback — must be in fallback list.** (1 connections) — `tests/contracts/test_dashscope_tools.py`
- **tts_selector should auto-discover dashscope_tts by capability.** (1 connections) — `tests/contracts/test_dashscope_tools.py`

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (13 shared connections)
- [Idempotency Key Tests](Idempotency_Key_Tests.md) (3 shared connections)
- [Tool Registry Discovery Tests](Tool_Registry_Discovery_Tests.md) (2 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (2 shared connections)
- [DashScope Contract Tests](DashScope_Contract_Tests.md) (1 shared connections)
- [TTS Provider Selector](TTS_Provider_Selector.md) (1 shared connections)
- [Composition Validator](Composition_Validator.md) (1 shared connections)

## Source Files

- `tests/contracts/test_dashscope_tools.py`
- `tools/audio/dashscope_tts.py`

## Audit Trail

- EXTRACTED: 42 (72%)
- INFERRED: 16 (28%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*