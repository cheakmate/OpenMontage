# Google TTS Tests

> 33 nodes · cohesion 0.11

## Key Concepts

- **GoogleTTS** (35 connections) — `tools/audio/google_tts.py`
- **has_google_credentials()** (13 connections) — `tools/google_credentials.py`
- **service_account_configured()** (9 connections) — `tools/google_credentials.py`
- **.execute()** (8 connections) — `tools/audio/google_tts.py`
- **.estimate_cost()** (6 connections) — `tools/audio/google_tts.py`
- **._generate()** (6 connections) — `tools/audio/google_tts.py`
- **._locale_from_voice()** (6 connections) — `tools/audio/google_tts.py`
- **test_google_tts_scoped_key.py** (6 connections) — `tests/tools/test_google_tts_scoped_key.py`
- **TestGoogleTTS** (5 connections) — `tests/contracts/test_phase3_contracts.py`
- **TestCostAndIdempotency** (5 connections) — `tests/tools/test_google_tts_voice_id_alias.py`
- **TestLocaleDerivation** (5 connections) — `tests/tools/test_google_tts_voice_id_alias.py`
- **.get_status()** (4 connections) — `tools/audio/google_tts.py`
- **.test_cost_estimate()** (3 connections) — `tests/contracts/test_phase3_contracts.py`
- **test_tts_key_uses_header_and_is_redacted_from_errors()** (3 connections) — `tests/tools/test_google_tts_scoped_key.py`
- **test_tts_only_key_does_not_enable_shared_google_providers()** (3 connections) — `tests/tools/test_google_tts_scoped_key.py`
- **.test_voice_id_matches_equivalent_voice_pricing()** (3 connections) — `tests/tools/test_google_tts_voice_id_alias.py`
- **.test_voice_id_selects_pricing_tier()** (3 connections) — `tests/tools/test_google_tts_voice_id_alias.py`
- **._get_api_key()** (3 connections) — `tools/audio/google_tts.py`
- **._needs_beta_api()** (3 connections) — `tools/audio/google_tts.py`
- **.get_status()** (3 connections) — `tools/graphics/google_imagen.py`
- **Any** (3 connections)
- **.test_capabilities()** (2 connections) — `tests/contracts/test_phase3_contracts.py`
- **.test_identity()** (2 connections) — `tests/contracts/test_phase3_contracts.py`
- **.test_voice_id_changes_idempotency_key()** (2 connections) — `tests/tools/test_google_tts_voice_id_alias.py`
- **.test_three_letter_prefix()** (2 connections) — `tests/tools/test_google_tts_voice_id_alias.py`
- *... and 8 more nodes in this community*

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (25 shared connections)
- [Google TTS Voice Tests](Google_TTS_Voice_Tests.md) (4 shared connections)
- [TTS Provider Tests](TTS_Provider_Tests.md) (3 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (3 shared connections)
- [Google Imagen Tests](Google_Imagen_Tests.md) (2 shared connections)
- [HyperFrames Runtime Tests](HyperFrames_Runtime_Tests.md) (1 shared connections)
- [Google Music Tests](Google_Music_Tests.md) (1 shared connections)
- [Veo Video Tests](Veo_Video_Tests.md) (1 shared connections)

## Source Files

- `tests/contracts/test_phase3_contracts.py`
- `tests/tools/test_google_tts_scoped_key.py`
- `tests/tools/test_google_tts_voice_id_alias.py`
- `tools/audio/gemini_tts.py`
- `tools/audio/google_tts.py`
- `tools/google_credentials.py`
- `tools/graphics/google_imagen.py`

## Audit Trail

- EXTRACTED: 80 (82%)
- INFERRED: 17 (18%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*