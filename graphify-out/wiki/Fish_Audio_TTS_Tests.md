# Fish Audio TTS Tests

> 62 nodes · cohesion 0.07

## Key Concepts

- **FishAudioTTS** (52 connections) — `tools/audio/fish_audio_tts.py`
- **test_fish_audio_tts.py** (20 connections) — `tests/tools/test_fish_audio_tts.py`
- **_FakeResponse** (11 connections) — `tests/tools/test_fish_audio_tts.py`
- **.estimate_cost()** (10 connections) — `tools/audio/fish_audio_tts.py`
- **.idempotency_key()** (9 connections) — `tools/audio/fish_audio_tts.py`
- **TestModelContract** (8 connections) — `tests/tools/test_fish_audio_tts.py`
- **.execute()** (8 connections) — `tools/audio/fish_audio_tts.py`
- **TestGenerate** (7 connections) — `tests/tools/test_fish_audio_tts.py`
- **TestIdempotencyKey** (7 connections) — `tests/tools/test_fish_audio_tts.py`
- **TestCost** (6 connections) — `tests/tools/test_fish_audio_tts.py`
- **TestStatus** (6 connections) — `tests/tools/test_fish_audio_tts.py`
- **._normalized_inputs()** (6 connections) — `tools/audio/fish_audio_tts.py`
- **Any** (6 connections)
- **._effective_inputs()** (5 connections) — `tools/audio/fish_audio_tts.py`
- **._generate()** (5 connections) — `tools/audio/fish_audio_tts.py`
- **api_key()** (4 connections) — `tests/tools/test_fish_audio_tts.py`
- **.test_output_affecting_controls_change_the_key()** (4 connections) — `tests/tools/test_fish_audio_tts.py`
- **.test_selector_call_with_model_id_and_voice_id_reaches_fish_audio()** (4 connections) — `tests/tools/test_fish_audio_tts.py`
- **TestKeyRedaction** (3 connections) — `tests/tools/test_fish_audio_tts.py`
- **TestRegistryMetadata** (3 connections) — `tests/tools/test_fish_audio_tts.py`
- **TestSelectorRouting** (3 connections) — `tests/tools/test_fish_audio_tts.py`
- **.test_cost_uses_utf8_bytes()** (3 connections) — `tests/tools/test_fish_audio_tts.py`
- **.test_estimate_cost_accepts_model_id_alias()** (3 connections) — `tests/tools/test_fish_audio_tts.py`
- **.test_s2_1_pro_free_charged_at_paid_rate_after_promo_window()** (3 connections) — `tests/tools/test_fish_audio_tts.py`
- **.test_s2_1_pro_free_costs_zero_during_promo_window()** (3 connections) — `tests/tools/test_fish_audio_tts.py`
- *... and 37 more nodes in this community*

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (15 shared connections)
- [TTS Provider Selector](TTS_Provider_Selector.md) (3 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (3 shared connections)
- [Kling Client Tests](Kling_Client_Tests.md) (1 shared connections)
- [Idempotency Cache Wrapper](Idempotency_Cache_Wrapper.md) (1 shared connections)
- [MiniMax Video Tests](MiniMax_Video_Tests.md) (1 shared connections)
- [Project Init Validation](Project_Init_Validation.md) (1 shared connections)
- [Event Logging](Event_Logging.md) (1 shared connections)
- [Tool Dependency Tests](Tool_Dependency_Tests.md) (1 shared connections)

## Source Files

- `tests/tools/test_fish_audio_tts.py`
- `tools/audio/fish_audio_tts.py`
- `tools/video/minimax_video.py`

## Audit Trail

- EXTRACTED: 122 (80%)
- INFERRED: 30 (20%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*