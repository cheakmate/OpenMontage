# Video Tool Tests

> 68 nodes · cohesion 0.06

## Key Concepts

- **VeoVideo** (32 connections) — `tools/video/veo_video.py`
- **GoogleMusic** (27 connections) — `tools/audio/google_music.py`
- **.execute()** (14 connections) — `tools/audio/google_music.py`
- **.execute()** (13 connections) — `tools/video/veo_video.py`
- **test_google_vertex_backends.py** (11 connections) — `tests/tools/test_google_vertex_backends.py`
- **TestVeoVideo** (10 connections) — `tests/contracts/test_phase3_contracts.py`
- **._execute_fal()** (10 connections) — `tools/video/veo_video.py`
- **._execute_google()** (10 connections) — `tools/video/veo_video.py`
- **TestGoogleMusic** (9 connections) — `tests/contracts/test_phase3_contracts.py`
- **._get_google_credentials_status()** (8 connections) — `tools/video/veo_video.py`
- **resolve_google_location()** (7 connections) — `tools/google_credentials.py`
- **.estimate_cost()** (7 connections) — `tools/video/veo_video.py`
- **._get_fal_api_key()** (7 connections) — `tools/video/veo_video.py`
- **.get_status()** (6 connections) — `tools/video/veo_video.py`
- **.test_backend_auto_detect()** (5 connections) — `tests/contracts/test_phase3_contracts.py`
- **.estimate_cost()** (5 connections) — `tools/audio/google_music.py`
- **._get_google_credentials_status()** (5 connections) — `tools/audio/google_music.py`
- **Any** (5 connections)
- **_Models** (4 connections) — `tests/tools/test_google_vertex_backends.py`
- **_VideoAsset** (4 connections) — `tests/tools/test_google_vertex_backends.py`
- **.test_multimodal_image()** (4 connections) — `tests/contracts/test_phase3_contracts.py`
- **.test_duration_coercion()** (4 connections) — `tests/contracts/test_phase3_contracts.py`
- **.test_operations_mapping()** (4 connections) — `tests/contracts/test_phase3_contracts.py`
- **test_veo_accepts_vertex_and_requires_inline_bytes()** (4 connections) — `tests/tools/test_google_vertex_backends.py`
- **.get_status()** (4 connections) — `tools/audio/google_music.py`
- *... and 43 more nodes in this community*

## Relationships

- [Core Utilities](Core_Utilities.md) (12 shared connections)
- [Tool Contracts](Tool_Contracts.md) (11 shared connections)
- [Tool Testing](Tool_Testing.md) (11 shared connections)
- [Character Animation](Character_Animation.md) (6 shared connections)
- [Tool Execution](Tool_Execution.md) (5 shared connections)
- [Image Generation Tests](Image_Generation_Tests.md) (1 shared connections)
- [Project Init](Project_Init.md) (1 shared connections)

## Source Files

- `tests/contracts/test_phase3_contracts.py`
- `tests/tools/test_google_vertex_backends.py`
- `tools/audio/google_music.py`
- `tools/google_credentials.py`
- `tools/video/veo_video.py`

## Audit Trail

- EXTRACTED: 135 (78%)
- INFERRED: 38 (22%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*