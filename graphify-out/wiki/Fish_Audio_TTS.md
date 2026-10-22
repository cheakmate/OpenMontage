# Fish Audio TTS

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

- [Tool Testing](Tool_Testing.md) (6 shared connections)
- [Core Utilities](Core_Utilities.md) (5 shared connections)
- [Tool Execution](Tool_Execution.md) (4 shared connections)
- [TTS Provider Selector](TTS_Provider_Selector.md) (3 shared connections)
- [Character Animation](Character_Animation.md) (3 shared connections)
- [Kling Tools](Kling_Tools.md) (1 shared connections)
- [Asset Cache Wrapper](Asset_Cache_Wrapper.md) (1 shared connections)
- [MiniMax Video](MiniMax_Video.md) (1 shared connections)
- [Project Init](Project_Init.md) (1 shared connections)
- [Event Stream](Event_Stream.md) (1 shared connections)
- [Visual Evaluation System](Visual_Evaluation_System.md) (1 shared connections)

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