# Tool Contract Tests

> 41 nodes · cohesion 0.10

## Key Concepts

- **AzureTTS** (44 connections) — `tools/audio/azure_tts.py`
- **TestContract** (9 connections) — `tests/tools/test_azure_tts.py`
- **TestExecute** (9 connections) — `tests/tools/test_azure_tts.py`
- **TestSSML** (9 connections) — `tests/tools/test_azure_tts.py`
- **._build_ssml()** (8 connections) — `tools/audio/azure_tts.py`
- **TestStatus** (7 connections) — `tests/tools/test_azure_tts.py`
- **._synthesize()** (7 connections) — `tools/audio/azure_tts.py`
- **_FakeResponse** (6 connections) — `tests/tools/test_azure_tts.py`
- **Any** (6 connections)
- **.test_selector_adapts_shared_controls_for_azure()** (5 connections) — `tests/tools/test_azure_tts.py`
- **.execute()** (5 connections) — `tools/audio/azure_tts.py`
- **fake_post()** (4 connections) — `tests/tools/test_azure_tts.py`
- **.test_wav_output_format()** (4 connections) — `tests/tools/test_azure_tts.py`
- **.estimate_cost()** (4 connections) — `tools/audio/azure_tts.py`
- **._resolve_voice()** (4 connections) — `tools/audio/azure_tts.py`
- **.test_estimate_cost_by_characters()** (3 connections) — `tests/tools/test_azure_tts.py`
- **.test_http_error_surfaced()** (3 connections) — `tests/tools/test_azure_tts.py`
- **.test_request_exception_surfaced()** (3 connections) — `tests/tools/test_azure_tts.py`
- **.test_success_path_mocked()** (3 connections) — `tests/tools/test_azure_tts.py`
- **.test_ssml_custom_locale()** (3 connections) — `tests/tools/test_azure_tts.py`
- **.test_ssml_escapes_xml()** (3 connections) — `tests/tools/test_azure_tts.py`
- **.test_ssml_prosody_and_voice()** (3 connections) — `tests/tools/test_azure_tts.py`
- **.test_ssml_quotes_in_attributes_remain_well_formed()** (3 connections) — `tests/tools/test_azure_tts.py`
- **.test_ssml_style_wrapping()** (3 connections) — `tests/tools/test_azure_tts.py`
- **.test_voice_alias_resolution()** (3 connections) — `tests/tools/test_azure_tts.py`
- *... and 16 more nodes in this community*

## Relationships

- [Tool Execution](Tool_Execution.md) (9 shared connections)
- [Core Utilities](Core_Utilities.md) (6 shared connections)
- [Tool Testing](Tool_Testing.md) (6 shared connections)
- [Character Animation](Character_Animation.md) (3 shared connections)
- [TTS Provider Selector](TTS_Provider_Selector.md) (2 shared connections)

## Source Files

- `tests/tools/test_azure_tts.py`
- `tools/audio/azure_tts.py`

## Audit Trail

- EXTRACTED: 79 (73%)
- INFERRED: 29 (27%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*