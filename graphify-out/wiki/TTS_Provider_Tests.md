# TTS Provider Tests

> 13 nodes · cohesion 0.24

## Key Concepts

- **OpenAITTS** (24 connections) — `tools/audio/openai_tts.py`
- **TestCapabilityMetadata** (9 connections) — `tests/contracts/test_phase3_contracts.py`
- **.test_provider_specific_tts_tools_register()** (9 connections) — `tests/contracts/test_phase3_contracts.py`
- **._generate()** (6 connections) — `tools/audio/openai_tts.py`
- **test_tts_provider_contracts_match_supported_fields()** (5 connections) — `tests/tools/test_hyperframes_compose.py`
- **.execute()** (5 connections) — `tools/audio/openai_tts.py`
- **.get_by_provider()** (4 connections) — `tools/tool_registry.py`
- **.estimate_cost()** (3 connections) — `tools/audio/openai_tts.py`
- **._supports_instructions()** (3 connections) — `tools/audio/openai_tts.py`
- **Any** (3 connections)
- **.test_tts_tools_expose_capability_provider_and_location()** (2 connections) — `tests/contracts/test_phase3_contracts.py`
- **.get_status()** (2 connections) — `tools/audio/openai_tts.py`
- **Get all tools backed by a specific provider.** (1 connections) — `tools/tool_registry.py`

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (14 shared connections)
- [ElevenLabs TTS Timestamps](ElevenLabs_TTS_Timestamps.md) (4 shared connections)
- [Piper TTS Tests](Piper_TTS_Tests.md) (4 shared connections)
- [ComfyUI Setup Registry](ComfyUI_Setup_Registry.md) (3 shared connections)
- [Tool Registry Discovery Tests](Tool_Registry_Discovery_Tests.md) (3 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (3 shared connections)
- [TTS Provider Selector](TTS_Provider_Selector.md) (2 shared connections)
- [HyperFrames Runtime Tests](HyperFrames_Runtime_Tests.md) (2 shared connections)
- [Tool Registry Discovery](Tool_Registry_Discovery.md) (1 shared connections)
- [Google TTS Tests](Google_TTS_Tests.md) (1 shared connections)
- [Composition Validator](Composition_Validator.md) (1 shared connections)

## Source Files

- `tests/contracts/test_phase3_contracts.py`
- `tests/tools/test_hyperframes_compose.py`
- `tools/audio/openai_tts.py`
- `tools/tool_registry.py`

## Audit Trail

- EXTRACTED: 36 (63%)
- INFERRED: 21 (37%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*