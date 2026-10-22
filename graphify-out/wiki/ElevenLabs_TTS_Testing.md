# ElevenLabs TTS Testing

> 25 nodes · cohesion 0.15

## Key Concepts

- **ElevenLabsTTS** (41 connections) — `tools/audio/elevenlabs_tts.py`
- **test_elevenlabs_timestamps.py** (15 connections) — `tests/tools/test_elevenlabs_timestamps.py`
- **TestCapabilityMetadata** (9 connections) — `tests/contracts/test_phase3_contracts.py`
- **TestElevenLabsTTS** (5 connections) — `tests/contracts/test_phase3_contracts.py`
- **.estimate_cost()** (5 connections) — `tools/audio/elevenlabs_tts.py`
- **.execute()** (5 connections) — `tools/audio/elevenlabs_tts.py`
- **._generate()** (5 connections) — `tools/audio/elevenlabs_tts.py`
- **.words_from_alignment()** (5 connections) — `tools/audio/elevenlabs_tts.py`
- **_json_response()** (4 connections) — `tests/tools/test_elevenlabs_timestamps.py`
- **Any** (4 connections)
- **.test_cost_estimate()** (3 connections) — `tests/contracts/test_phase3_contracts.py`
- **test_with_timestamps_calls_endpoint_and_returns_words()** (3 connections) — `tests/tools/test_elevenlabs_timestamps.py`
- **test_with_timestamps_pcm_output_is_wrapped_as_wav()** (3 connections) — `tests/tools/test_elevenlabs_timestamps.py`
- **test_words_from_alignment_handles_multichar_entries()** (3 connections) — `tests/tools/test_elevenlabs_timestamps.py`
- **.test_tts_tools_expose_capability_provider_and_location()** (2 connections) — `tests/contracts/test_phase3_contracts.py`
- **.test_capabilities()** (2 connections) — `tests/contracts/test_phase3_contracts.py`
- **.test_identity()** (2 connections) — `tests/contracts/test_phase3_contracts.py`
- **_alignment()** (2 connections) — `tests/tools/test_elevenlabs_timestamps.py`
- **test_default_path_is_unchanged()** (2 connections) — `tests/tools/test_elevenlabs_timestamps.py`
- **test_missing_alignment_fails_loudly()** (2 connections) — `tests/tools/test_elevenlabs_timestamps.py`
- **test_with_timestamps_is_part_of_idempotency_key()** (2 connections) — `tests/tools/test_elevenlabs_timestamps.py`
- **test_direct_eleven_v4_continuity_and_pcm()** (2 connections) — `tests/tools/test_provider_refresh.py`
- **.get_status()** (2 connections) — `tools/audio/elevenlabs_tts.py`
- **ElevenLabs TTS: optional word-level timings via the /with-timestamps endpoint.** (1 connections) — `tests/tools/test_elevenlabs_timestamps.py`
- **Group ElevenLabs character timings into whitespace-delimited words. Each word…** (1 connections) — `tools/audio/elevenlabs_tts.py`

## Relationships

- [Core Utilities](Core_Utilities.md) (10 shared connections)
- [Tool Registry](Tool_Registry.md) (6 shared connections)
- [Tool Contracts](Tool_Contracts.md) (4 shared connections)
- [Tool Testing](Tool_Testing.md) (4 shared connections)
- [Provider Refresh](Provider_Refresh.md) (3 shared connections)
- [Character Animation](Character_Animation.md) (3 shared connections)
- [Tool Registry Testing](Tool_Registry_Testing.md) (2 shared connections)
- [TTS Provider Tests](TTS_Provider_Tests.md) (2 shared connections)
- [Tool Execution](Tool_Execution.md) (2 shared connections)
- [TTS Provider Selector](TTS_Provider_Selector.md) (1 shared connections)
- [Style Bridge](Style_Bridge.md) (1 shared connections)
- [Hexagon Cube Visualization](Hexagon_Cube_Visualization.md) (1 shared connections)

## Source Files

- `tests/contracts/test_phase3_contracts.py`
- `tests/tools/test_elevenlabs_timestamps.py`
- `tests/tools/test_provider_refresh.py`
- `tools/audio/elevenlabs_tts.py`

## Audit Trail

- EXTRACTED: 64 (75%)
- INFERRED: 21 (25%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*