# Fal TTS Testing

> 19 nodes · cohesion 0.21

## Key Concepts

- **FalElevenLabsTTS** (30 connections) — `tools/audio/fal_elevenlabs_tts.py`
- **test_fal_elevenlabs_tts.py** (16 connections) — `tests/tools/test_fal_elevenlabs_tts.py`
- **.execute()** (9 connections) — `tools/audio/fal_elevenlabs_tts.py`
- **.estimate_cost()** (6 connections) — `tools/audio/fal_elevenlabs_tts.py`
- **test_contract_models_and_cost()** (5 connections) — `tests/tools/test_fal_elevenlabs_tts.py`
- **test_tts_selector_routes_to_fal_provider()** (5 connections) — `tests/tools/test_fal_elevenlabs_tts.py`
- **._run_job()** (5 connections) — `tools/audio/fal_elevenlabs_tts.py`
- **test_execute_submits_once_and_downloads_audio()** (4 connections) — `tests/tools/test_fal_elevenlabs_tts.py`
- **test_fal_v4_native_fields_and_resume()** (4 connections) — `tests/tools/test_provider_refresh.py`
- **.get_status()** (4 connections) — `tools/audio/fal_elevenlabs_tts.py`
- **._get_api_key()** (3 connections) — `tools/audio/fal_elevenlabs_tts.py`
- **._resolve_model()** (3 connections) — `tools/audio/fal_elevenlabs_tts.py`
- **_response()** (2 connections) — `tests/tools/test_fal_elevenlabs_tts.py`
- **test_error_redacts_fal_key()** (2 connections) — `tests/tools/test_fal_elevenlabs_tts.py`
- **test_invalid_model_does_not_submit()** (2 connections) — `tests/tools/test_fal_elevenlabs_tts.py`
- **response()** (2 connections) — `tests/tools/test_provider_refresh.py`
- **._output_extension()** (2 connections) — `tools/audio/fal_elevenlabs_tts.py`
- **Any** (2 connections)
- **Generate expressive narration with ElevenLabs models hosted by fal.ai.** (1 connections) — `tools/audio/fal_elevenlabs_tts.py`

## Relationships

- [Core Utilities](Core_Utilities.md) (11 shared connections)
- [Tool Execution](Tool_Execution.md) (5 shared connections)
- [Character Animation](Character_Animation.md) (5 shared connections)
- [Tool Testing](Tool_Testing.md) (4 shared connections)
- [Provider Refresh](Provider_Refresh.md) (3 shared connections)
- [TTS Provider Selector](TTS_Provider_Selector.md) (3 shared connections)
- [Three.js Asset Catalog](Three.js_Asset_Catalog.md) (1 shared connections)
- [Tool Registry](Tool_Registry.md) (1 shared connections)
- [Visual Evaluation System](Visual_Evaluation_System.md) (1 shared connections)
- [Atlas Tool Tests](Atlas_Tool_Tests.md) (1 shared connections)

## Source Files

- `tests/tools/test_fal_elevenlabs_tts.py`
- `tests/tools/test_provider_refresh.py`
- `tools/audio/fal_elevenlabs_tts.py`

## Audit Trail

- EXTRACTED: 53 (75%)
- INFERRED: 18 (25%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*