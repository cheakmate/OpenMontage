# Fake Response Handler

> 22 nodes · cohesion 0.13

## Key Concepts

- **FakeResponse** (10 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **_install_fake_requests()** (10 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **TestExecuteWithMocks** (9 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **.test_i2v_with_local_image_path()** (5 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **.test_image_to_video_with_url_success()** (5 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **.test_polling_fails_on_task_failed()** (5 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **.test_polling_retries_until_success()** (5 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **.test_submit_error_returns_failure()** (5 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **.test_text_to_video_success()** (5 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **.test_explicit_incompatible_model_is_rejected()** (2 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **.__init__()** (1 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **.json()** (1 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **.raise_for_status()** (1 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **fake_get()** (1 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **fake_post()** (1 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **Full T2V flow: submit -> poll -> download -> write output.** (1 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **Inject a fake requests module; returns the recorded calls.** (1 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **Full I2V flow with an image URL.** (1 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **Full I2V flow with a local image path -> base64 encoding.** (1 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **Polling should retry when status is queued/running, then succeed.** (1 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **When the API returns status=failed, execute should return error.** (1 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **API-level error on submit should be returned as ToolResult error.** (1 connections) — `tests/contracts/test_hunyuan_cloud_video.py`

## Relationships

- [Tool Contract Tests](Tool_Contract_Tests.md) (8 shared connections)
- [Core Utilities](Core_Utilities.md) (3 shared connections)

## Source Files

- `tests/contracts/test_hunyuan_cloud_video.py`

## Audit Trail

- EXTRACTED: 39 (93%)
- INFERRED: 3 (7%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*