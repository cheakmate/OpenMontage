# Veo Video Tests

> 33 nodes · cohesion 0.13

## Key Concepts

- **VeoVideo** (32 connections) — `tools/video/veo_video.py`
- **.execute()** (13 connections) — `tools/video/veo_video.py`
- **TestVeoVideo** (10 connections) — `tests/contracts/test_phase3_contracts.py`
- **._execute_fal()** (10 connections) — `tools/video/veo_video.py`
- **._execute_google()** (10 connections) — `tools/video/veo_video.py`
- **._get_google_credentials_status()** (8 connections) — `tools/video/veo_video.py`
- **.estimate_cost()** (7 connections) — `tools/video/veo_video.py`
- **._get_fal_api_key()** (7 connections) — `tools/video/veo_video.py`
- **.get_status()** (6 connections) — `tools/video/veo_video.py`
- **.test_backend_auto_detect()** (5 connections) — `tests/contracts/test_phase3_contracts.py`
- **Any** (5 connections)
- **.test_duration_coercion()** (4 connections) — `tests/contracts/test_phase3_contracts.py`
- **.test_operations_mapping()** (4 connections) — `tests/contracts/test_phase3_contracts.py`
- **.estimate_runtime()** (4 connections) — `tools/video/veo_video.py`
- **._file_to_data_uri()** (4 connections) — `tools/video/veo_video.py`
- **._normalize_file_input()** (4 connections) — `tools/video/veo_video.py`
- **.test_missing_local_image_paths()** (3 connections) — `tests/contracts/test_phase3_contracts.py`
- **.test_missing_reference_image_paths()** (3 connections) — `tests/contracts/test_phase3_contracts.py`
- **.test_vertex_ai_mode_requires_inline_video_bytes()** (3 connections) — `tests/contracts/test_phase3_contracts.py`
- **patch** (3 connections)
- **.test_identity()** (2 connections) — `tests/contracts/test_phase3_contracts.py`
- **_get_image()** (1 connections) — `tools/video/veo_video.py`
- **_to_sdk_image()** (1 connections) — `tools/video/veo_video.py`
- **Check whether Google API keys or Vertex AI service account credentials are set.** (1 connections) — `tools/video/veo_video.py`
- **Retrieve the FAL API key from environment variables.** (1 connections) — `tools/video/veo_video.py`
- *... and 8 more nodes in this community*

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (15 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (4 shared connections)
- [Vertex Video Backend Tests](Vertex_Video_Backend_Tests.md) (2 shared connections)
- [CogVideo Variant Tests](CogVideo_Variant_Tests.md) (2 shared connections)
- [Google TTS Tests](Google_TTS_Tests.md) (1 shared connections)
- [Google Music Tests](Google_Music_Tests.md) (1 shared connections)

## Source Files

- `tests/contracts/test_phase3_contracts.py`
- `tools/video/veo_video.py`

## Audit Trail

- EXTRACTED: 72 (78%)
- INFERRED: 20 (22%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*