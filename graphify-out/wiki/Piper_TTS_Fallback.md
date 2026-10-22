# Piper TTS Fallback

> 20 nodes · cohesion 0.18

## Key Concepts

- **DashscopeTTS** (31 connections) — `tools/audio/dashscope_tts.py`
- **TestDashscopeTtsSpecific** (10 connections) — `tests/contracts/test_dashscope_tools.py`
- **.execute()** (7 connections) — `tools/audio/dashscope_tts.py`
- **._build_payload()** (5 connections) — `tools/audio/dashscope_tts.py`
- **.estimate_cost()** (4 connections) — `tools/audio/dashscope_tts.py`
- **._safe_error()** (4 connections) — `tools/audio/dashscope_tts.py`
- **.test_build_payload_adds_instructions_for_instruct_model()** (3 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_build_payload_includes_input_text_voice()** (3 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_cost_scales_with_text_length()** (3 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_fallback_includes_piper()** (3 connections) — `tests/contracts/test_dashscope_tools.py`
- **Any** (3 connections)
- **.test_tts_idempotency_differs_on_instructions()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_tts_idempotency_includes_instructions()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_default_language_is_auto()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_default_model_is_qwen3_tts_flash()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_default_voice_is_cherry()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_safe_error_redacts_key()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.get_status()** (2 connections) — `tools/audio/dashscope_tts.py`
- **Exception** (1 connections)
- **Piper is the free offline fallback — must be in fallback list.** (1 connections) — `tests/contracts/test_dashscope_tools.py`

## Relationships

- [Tool Testing](Tool_Testing.md) (7 shared connections)
- [Core Utilities](Core_Utilities.md) (4 shared connections)
- [DashScope API Testing](DashScope_API_Testing.md) (3 shared connections)
- [Dashscope Registry Tests](Dashscope_Registry_Tests.md) (2 shared connections)
- [Tool Execution](Tool_Execution.md) (2 shared connections)
- [Character Animation](Character_Animation.md) (2 shared connections)
- [Tool Contract Testing](Tool_Contract_Testing.md) (1 shared connections)
- [TTS Provider Tests](TTS_Provider_Tests.md) (1 shared connections)

## Source Files

- `tests/contracts/test_dashscope_tools.py`
- `tools/audio/dashscope_tts.py`

## Audit Trail

- EXTRACTED: 41 (72%)
- INFERRED: 16 (28%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*