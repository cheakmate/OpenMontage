# Tool Contracts

> 68 nodes · cohesion 0.05

## Key Concepts

- **test_phase3_contracts.py** (63 connections) — `tests/contracts/test_phase3_contracts.py`
- **GoogleTTS** (35 connections) — `tools/audio/google_tts.py`
- **GoogleImagen** (30 connections) — `tools/graphics/google_imagen.py`
- **google_imagen.py** (29 connections) — `tools/graphics/google_imagen.py`
- **PiperTTS** (27 connections) — `tools/audio/piper_tts.py`
- **google_tts.py** (24 connections) — `tools/audio/google_tts.py`
- **GeminiTTS** (16 connections) — `tools/audio/gemini_tts.py`
- **get_genai_client()** (16 connections) — `tools/google_credentials.py`
- **has_google_credentials()** (13 connections) — `tools/google_credentials.py`
- **google_credentials.py** (13 connections) — `tools/google_credentials.py`
- **service_account_configured()** (9 connections) — `tools/google_credentials.py`
- **.execute()** (8 connections) — `tools/audio/google_tts.py`
- **TestPiperTTS** (7 connections) — `tests/contracts/test_phase3_contracts.py`
- **.estimate_cost()** (6 connections) — `tools/audio/google_tts.py`
- **._generate()** (6 connections) — `tools/audio/google_tts.py`
- **get_access_token()** (6 connections) — `tools/google_credentials.py`
- **test_google_tts_scoped_key.py** (6 connections) — `tests/tools/test_google_tts_scoped_key.py`
- **TestGoogleTTS** (5 connections) — `tests/contracts/test_phase3_contracts.py`
- **TestCostAndIdempotency** (5 connections) — `tests/tools/test_google_tts_voice_id_alias.py`
- **.execute()** (5 connections) — `tools/audio/gemini_tts.py`
- **.execute()** (5 connections) — `tools/audio/piper_tts.py`
- **resolve_project_id()** (5 connections) — `tools/google_credentials.py`
- **TestGoogleImagen** (4 connections) — `tests/contracts/test_phase3_contracts.py`
- **.test_status_requires_piper_executable_even_if_python_package_imports()** (4 connections) — `tests/contracts/test_phase3_contracts.py`
- **.get_status()** (4 connections) — `tools/audio/google_tts.py`
- *... and 43 more nodes in this community*

## Relationships

- [Core Utilities](Core_Utilities.md) (49 shared connections)
- [Tool Testing](Tool_Testing.md) (38 shared connections)
- [Tool Execution](Tool_Execution.md) (12 shared connections)
- [Image Generation Tests](Image_Generation_Tests.md) (12 shared connections)
- [Character Animation](Character_Animation.md) (11 shared connections)
- [Video Tool Tests](Video_Tool_Tests.md) (11 shared connections)
- [Pipeline Loader](Pipeline_Loader.md) (8 shared connections)
- [Google TTS Voice Testing](Google_TTS_Voice_Testing.md) (7 shared connections)
- [Tool Registry](Tool_Registry.md) (6 shared connections)
- [ElevenLabs TTS Testing](ElevenLabs_TTS_Testing.md) (4 shared connections)
- [Google Imagen Testing](Google_Imagen_Testing.md) (4 shared connections)
- [Playbook Validation](Playbook_Validation.md) (4 shared connections)

## Source Files

- `tests/contracts/test_phase3_contracts.py`
- `tests/tools/test_google_tts_scoped_key.py`
- `tests/tools/test_google_tts_voice_id_alias.py`
- `tests/tools/test_provider_refresh.py`
- `tools/audio/gemini_tts.py`
- `tools/audio/google_tts.py`
- `tools/audio/piper_tts.py`
- `tools/google_credentials.py`
- `tools/graphics/google_imagen.py`

## Audit Trail

- EXTRACTED: 260 (83%)
- INFERRED: 54 (17%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*