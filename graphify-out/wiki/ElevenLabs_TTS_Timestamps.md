# ElevenLabs TTS Timestamps

> 23 nodes · cohesion 0.17

## Key Concepts

- **ElevenLabsTTS** (41 connections) — `tools/audio/elevenlabs_tts.py`
- **test_elevenlabs_timestamps.py** (15 connections) — `tests/tools/test_elevenlabs_timestamps.py`
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

- [Tool Base Runtime](Tool_Base_Runtime.md) (15 shared connections)
- [TTS Provider Tests](TTS_Provider_Tests.md) (7 shared connections)
- [Piper TTS Tests](Piper_TTS_Tests.md) (3 shared connections)
- [Provider Contract Tests](Provider_Contract_Tests.md) (3 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (3 shared connections)
- [ComfyUI Setup Registry](ComfyUI_Setup_Registry.md) (1 shared connections)
- [HyperFrames Runtime Tests](HyperFrames_Runtime_Tests.md) (1 shared connections)
- [Scene Pacing Verification](Scene_Pacing_Verification.md) (1 shared connections)
- [Tool Dependency Tests](Tool_Dependency_Tests.md) (1 shared connections)

## Source Files

- `tests/contracts/test_phase3_contracts.py`
- `tests/tools/test_elevenlabs_timestamps.py`
- `tests/tools/test_provider_refresh.py`
- `tools/audio/elevenlabs_tts.py`

## Audit Trail

- EXTRACTED: 60 (78%)
- INFERRED: 17 (22%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*