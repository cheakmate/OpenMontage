# Google TTS Voice Testing

> 22 nodes · cohesion 0.13

## Key Concepts

- **test_google_tts_voice_id_alias.py** (13 connections) — `tests/tools/test_google_tts_voice_id_alias.py`
- **_execute()** (7 connections) — `tests/tools/test_google_tts_voice_id_alias.py`
- **TestVoiceIdAlias** (6 connections) — `tests/tools/test_google_tts_voice_id_alias.py`
- **._locale_from_voice()** (6 connections) — `tools/audio/google_tts.py`
- **TestLocaleDerivation** (5 connections) — `tests/tools/test_google_tts_voice_id_alias.py`
- **_FakeResponse** (4 connections) — `tests/tools/test_google_tts_voice_id_alias.py`
- **captured_synthesize()** (4 connections) — `tests/tools/test_google_tts_voice_id_alias.py`
- **fake_post()** (2 connections) — `tests/tools/test_google_tts_voice_id_alias.py`
- **.test_three_letter_prefix()** (2 connections) — `tests/tools/test_google_tts_voice_id_alias.py`
- **.test_two_letter_prefix()** (2 connections) — `tests/tools/test_google_tts_voice_id_alias.py`
- **.test_unparseable_name_falls_back_to_en_us()** (2 connections) — `tests/tools/test_google_tts_voice_id_alias.py`
- **.test_chirp_voice_id_routes_to_beta_endpoint()** (2 connections) — `tests/tools/test_google_tts_voice_id_alias.py`
- **.test_default_voice_when_neither_field_set()** (2 connections) — `tests/tools/test_google_tts_voice_id_alias.py`
- **.test_explicit_language_code_wins_over_derived()** (2 connections) — `tests/tools/test_google_tts_voice_id_alias.py`
- **.test_explicit_voice_wins_over_voice_id()** (2 connections) — `tests/tools/test_google_tts_voice_id_alias.py`
- **.test_voice_id_sets_voice_name_and_derived_language()** (2 connections) — `tests/tools/test_google_tts_voice_id_alias.py`
- **.json()** (1 connections) — `tests/tools/test_google_tts_voice_id_alias.py`
- **.raise_for_status()** (1 connections) — `tests/tools/test_google_tts_voice_id_alias.py`
- **fixture** (1 connections)
- **Regression tests for google_tts voice_id alias + language_code derivation.…** (1 connections) — `tests/tools/test_google_tts_voice_id_alias.py`
- **Route requests.post to a fake and capture the synthesize call.** (1 connections) — `tests/tools/test_google_tts_voice_id_alias.py`
- **Derive the BCP-47 locale from a voice name like ja-JP-Chirp3-HD-Kore.** (1 connections) — `tools/audio/google_tts.py`

## Relationships

- [Tool Contracts](Tool_Contracts.md) (7 shared connections)
- [Core Utilities](Core_Utilities.md) (2 shared connections)
- [Lyria BGM Generation](Lyria_BGM_Generation.md) (1 shared connections)
- [Project Init](Project_Init.md) (1 shared connections)

## Source Files

- `tests/tools/test_google_tts_voice_id_alias.py`
- `tools/audio/google_tts.py`

## Audit Trail

- EXTRACTED: 38 (95%)
- INFERRED: 2 (5%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*