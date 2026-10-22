# TTS Provider Selector

> 19 nodes · cohesion 0.22

## Key Concepts

- **TTSSelector** (32 connections) — `tools/audio/tts_selector.py`
- **.execute()** (12 connections) — `tools/audio/tts_selector.py`
- **._providers()** (8 connections) — `tools/audio/tts_selector.py`
- **._select_best_tool()** (8 connections) — `tools/audio/tts_selector.py`
- **Any** (7 connections)
- **test_tts_selector_routes_to_fal_provider()** (5 connections) — `tests/tools/test_fal_elevenlabs_tts.py`
- **._adapt_inputs()** (5 connections) — `tools/audio/tts_selector.py`
- **.estimate_cost()** (5 connections) — `tools/audio/tts_selector.py`
- **._prepare_task_context()** (5 connections) — `tools/audio/tts_selector.py`
- **._tool_context_payload()** (5 connections) — `tools/audio/tts_selector.py`
- **._serialize_rankings()** (4 connections) — `tools/audio/tts_selector.py`
- **.fallback_tools()** (3 connections) — `tools/audio/tts_selector.py`
- **.provider_matrix()** (3 connections) — `tools/audio/tts_selector.py`
- **.get_status()** (3 connections) — `tools/audio/tts_selector.py`
- **Auto-discover TTS providers from the registry.** (1 connections) — `tools/audio/tts_selector.py`
- **Dynamically built from discovered providers.** (1 connections) — `tools/audio/tts_selector.py`
- **Built at runtime from each provider's best_for field.** (1 connections) — `tools/audio/tts_selector.py`
- **Translate capability-level controls to provider-native inputs.** (1 connections) — `tools/audio/tts_selector.py`
- **Select the best TTS provider using scored ranking.** (1 connections) — `tools/audio/tts_selector.py`

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (15 shared connections)
- [Fish Audio TTS Tests](Fish_Audio_TTS_Tests.md) (3 shared connections)
- [ElevenLabs TTS Tests](ElevenLabs_TTS_Tests.md) (3 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (3 shared connections)
- [Provider Scoring](Provider_Scoring.md) (3 shared connections)
- [TTS Provider Tests](TTS_Provider_Tests.md) (2 shared connections)
- [Tool Contract Tests](Tool_Contract_Tests.md) (2 shared connections)
- [Provider Contract Tests](Provider_Contract_Tests.md) (2 shared connections)
- [DashScope TTS Tests](DashScope_TTS_Tests.md) (1 shared connections)
- [Tool Registry Discovery Tests](Tool_Registry_Discovery_Tests.md) (1 shared connections)
- [Image Selector Tests](Image_Selector_Tests.md) (1 shared connections)

## Source Files

- `tests/tools/test_fal_elevenlabs_tts.py`
- `tools/audio/tts_selector.py`

## Audit Trail

- EXTRACTED: 62 (85%)
- INFERRED: 11 (15%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*