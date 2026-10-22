# Google Music Tests

> 19 nodes · cohesion 0.20

## Key Concepts

- **GoogleMusic** (27 connections) — `tools/audio/google_music.py`
- **.execute()** (14 connections) — `tools/audio/google_music.py`
- **TestGoogleMusic** (9 connections) — `tests/contracts/test_phase3_contracts.py`
- **.estimate_cost()** (5 connections) — `tools/audio/google_music.py`
- **._get_google_credentials_status()** (5 connections) — `tools/audio/google_music.py`
- **.test_multimodal_image()** (4 connections) — `tests/contracts/test_phase3_contracts.py`
- **.get_status()** (4 connections) — `tools/audio/google_music.py`
- **.test_duration_validation()** (3 connections) — `tests/contracts/test_phase3_contracts.py`
- **.test_execute_success_convenience_extraction()** (3 connections) — `tests/contracts/test_phase3_contracts.py`
- **.test_execute_success_fallback_extraction()** (3 connections) — `tests/contracts/test_phase3_contracts.py`
- **.test_minimum_duration_validation()** (3 connections) — `tests/contracts/test_phase3_contracts.py`
- **.test_missing_image_path_error()** (3 connections) — `tests/contracts/test_phase3_contracts.py`
- **.test_identity()** (2 connections) — `tests/contracts/test_phase3_contracts.py`
- **Any** (2 connections)
- **_get_image_data()** (1 connections) — `tools/audio/google_music.py`
- **Check whether Google API keys or Vertex AI service account credentials are set.** (1 connections) — `tools/audio/google_music.py`
- **Determine whether the tool is available based on configured credentials.** (1 connections) — `tools/audio/google_music.py`
- **Estimate the generation cost in USD.** (1 connections) — `tools/audio/google_music.py`
- **Execute the music generation tool using the Google GenAI SDK.** (1 connections) — `tools/audio/google_music.py`

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (14 shared connections)
- [Vertex Video Backend Tests](Vertex_Video_Backend_Tests.md) (2 shared connections)
- [TTS Provider Tests](TTS_Provider_Tests.md) (2 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (2 shared connections)
- [Veo Video Tests](Veo_Video_Tests.md) (1 shared connections)
- [Google TTS Tests](Google_TTS_Tests.md) (1 shared connections)

## Source Files

- `tests/contracts/test_phase3_contracts.py`
- `tools/audio/google_music.py`

## Audit Trail

- EXTRACTED: 40 (70%)
- INFERRED: 17 (30%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*