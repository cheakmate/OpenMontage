# Auth Header Testing

> 24 nodes · cohesion 0.12

## Key Concepts

- **._generate()** (10 connections) — `tools/video/hunyuan_cloud_video.py`
- **._resolve_model()** (9 connections) — `tools/video/hunyuan_cloud_video.py`
- **Any** (9 connections)
- **.execute()** (7 connections) — `tools/video/hunyuan_cloud_video.py`
- **._json_or_raise()** (7 connections) — `tools/video/hunyuan_cloud_video.py`
- **._submit_task()** (7 connections) — `tools/video/hunyuan_cloud_video.py`
- **._poll_task()** (6 connections) — `tools/video/hunyuan_cloud_video.py`
- **._auth_headers()** (5 connections) — `tools/video/hunyuan_cloud_video.py`
- **.estimate_cost()** (5 connections) — `tools/video/hunyuan_cloud_video.py`
- **TestAuthHeaders** (3 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **._api_key()** (3 connections) — `tools/video/hunyuan_cloud_video.py`
- **.estimate_runtime()** (3 connections) — `tools/video/hunyuan_cloud_video.py`
- **.get_status()** (3 connections) — `tools/video/hunyuan_cloud_video.py`
- **.test_auth_headers_includes_bearer()** (2 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **.test_resolve_model_defaults_i2v()** (2 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **.test_resolve_model_defaults_t2v()** (2 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **.test_resolve_model_explicit_input()** (2 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **Estimate cost in USD based on model and resolution. Tencent TokenHub credit-…** (1 connections) — `tools/video/hunyuan_cloud_video.py`
- **Estimate wall-clock time in seconds. Empirical estimate: most cloud video…** (1 connections) — `tools/video/hunyuan_cloud_video.py`
- **Resolve the TokenHub model ID. Order of precedence: 1. Explicit ``model`` input…** (1 connections) — `tools/video/hunyuan_cloud_video.py`
- **Build common request headers for TokenHub API calls.** (1 connections) — `tools/video/hunyuan_cloud_video.py`
- **Submit a video generation task and return the task ID.** (1 connections) — `tools/video/hunyuan_cloud_video.py`
- **Poll /v1/api/video/query until completion, return video download URL.** (1 connections) — `tools/video/hunyuan_cloud_video.py`
- **Parse JSON response body or raise with HTTP status.** (1 connections) — `tools/video/hunyuan_cloud_video.py`

## Relationships

- [Tool Contract Tests](Tool_Contract_Tests.md) (12 shared connections)
- [Text-to-Video Testing](Text-to-Video_Testing.md) (5 shared connections)
- [Error Helper Tests](Error_Helper_Tests.md) (5 shared connections)
- [Character Animation](Character_Animation.md) (2 shared connections)
- [Core Utilities](Core_Utilities.md) (1 shared connections)
- [Safe Error Tests](Safe_Error_Tests.md) (1 shared connections)
- [Tool Testing](Tool_Testing.md) (1 shared connections)
- [Tool Execution](Tool_Execution.md) (1 shared connections)

## Source Files

- `tests/contracts/test_hunyuan_cloud_video.py`
- `tools/video/hunyuan_cloud_video.py`

## Audit Trail

- EXTRACTED: 59 (98%)
- INFERRED: 1 (2%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*