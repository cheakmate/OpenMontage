# Provider Model Defaults

> 20 nodes · cohesion 0.15

## Key Concepts

- **RunwayVideo** (20 connections) — `tools/video/runway_video.py`
- **HiggsFieldVideo** (17 connections) — `tools/video/higgsfield_video.py`
- **test_provider_model_defaults.py** (8 connections) — `tests/tools/test_provider_model_defaults.py`
- **.execute()** (7 connections) — `tools/video/runway_video.py`
- **.execute()** (6 connections) — `tools/video/higgsfield_video.py`
- **._get_credentials()** (4 connections) — `tools/video/higgsfield_video.py`
- **.estimate_cost()** (3 connections) — `tools/video/higgsfield_video.py`
- **.get_status()** (3 connections) — `tools/video/higgsfield_video.py`
- **.estimate_cost()** (3 connections) — `tools/video/runway_video.py`
- **Any** (3 connections)
- **Any** (3 connections)
- **test_default_model_constant_matches_schema()** (2 connections) — `tests/tools/test_provider_model_defaults.py`
- **test_estimate_default_model_matches_schema()** (2 connections) — `tests/tools/test_provider_model_defaults.py`
- **.estimate_runtime()** (2 connections) — `tools/video/higgsfield_video.py`
- **.estimate_runtime()** (2 connections) — `tools/video/runway_video.py`
- **._get_api_key()** (2 connections) — `tools/video/runway_video.py`
- **.get_status()** (2 connections) — `tools/video/runway_video.py`
- **parametrize** (2 connections)
- **Regression: a provider's code-level model default must match its schema's…** (1 connections) — `tests/tools/test_provider_model_defaults.py`
- **Return (api_key, api_secret) or None if not configured.** (1 connections) — `tools/video/higgsfield_video.py`

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (24 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (4 shared connections)
- [Video Model Provider Tests](Video_Model_Provider_Tests.md) (4 shared connections)
- [CogVideo Variant Tests](CogVideo_Variant_Tests.md) (2 shared connections)
- [Project Init Validation](Project_Init_Validation.md) (1 shared connections)

## Source Files

- `tests/tools/test_provider_model_defaults.py`
- `tools/video/higgsfield_video.py`
- `tools/video/runway_video.py`

## Audit Trail

- EXTRACTED: 45 (70%)
- INFERRED: 19 (30%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*