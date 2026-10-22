# TTS Provider Tests

> 17 nodes · cohesion 0.18

## Key Concepts

- **OpenAITTS** (24 connections) — `tools/audio/openai_tts.py`
- **CompositionValidator** (16 connections) — `tools/analysis/composition_validator.py`
- **probe_duration()** (16 connections) — `tools/analysis/audio_probe.py`
- **._generate()** (6 connections) — `tools/audio/openai_tts.py`
- **test_tts_provider_contracts_match_supported_fields()** (5 connections) — `tests/tools/test_hyperframes_compose.py`
- **.execute()** (5 connections) — `tools/analysis/composition_validator.py`
- **.execute()** (5 connections) — `tools/audio/openai_tts.py`
- **._result()** (3 connections) — `tools/analysis/composition_validator.py`
- **.estimate_cost()** (3 connections) — `tools/audio/openai_tts.py`
- **._supports_instructions()** (3 connections) — `tools/audio/openai_tts.py`
- **Any** (3 connections)
- **.estimate_cost()** (2 connections) — `tools/analysis/composition_validator.py`
- **.get_status()** (2 connections) — `tools/analysis/composition_validator.py`
- **.get_status()** (2 connections) — `tools/audio/openai_tts.py`
- **Any** (2 connections)
- **Path** (1 connections)
- **Quick helper: return duration in seconds, or None on failure. Use this from…** (1 connections) — `tools/analysis/audio_probe.py`

## Relationships

- [Core Utilities](Core_Utilities.md) (13 shared connections)
- [Tool Testing](Tool_Testing.md) (11 shared connections)
- [Character Animation](Character_Animation.md) (6 shared connections)
- [Style Bridge](Style_Bridge.md) (4 shared connections)
- [Tool Execution](Tool_Execution.md) (4 shared connections)
- [Tool Registry](Tool_Registry.md) (3 shared connections)
- [Tool Contracts](Tool_Contracts.md) (2 shared connections)
- [ElevenLabs TTS Testing](ElevenLabs_TTS_Testing.md) (2 shared connections)
- [Tool Registry Testing](Tool_Registry_Testing.md) (1 shared connections)
- [Audio Mixing](Audio_Mixing.md) (1 shared connections)
- [Piper TTS Fallback](Piper_TTS_Fallback.md) (1 shared connections)
- [Doubao TTS Provider](Doubao_TTS_Provider.md) (1 shared connections)

## Source Files

- `tests/tools/test_hyperframes_compose.py`
- `tools/analysis/audio_probe.py`
- `tools/analysis/composition_validator.py`
- `tools/audio/openai_tts.py`

## Audit Trail

- EXTRACTED: 53 (71%)
- INFERRED: 22 (29%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*