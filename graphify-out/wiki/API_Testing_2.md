# API Testing

> 30 nodes · cohesion 0.10

## Key Concepts

- **_FakeResponse** (20 connections) — `tests/contracts/test_seedance_ark_video.py`
- **fake_post()** (8 connections) — `tests/contracts/test_seedance_ark_video.py`
- **TestTaskActions** (6 connections) — `tests/contracts/test_seedance_ark_video.py`
- **.test_download_errors_redact_signed_url_and_preserve_task_id()** (6 connections) — `tests/contracts/test_seedance_ark_video.py`
- **.test_terminal_failure_redacts_signed_input_url()** (6 connections) — `tests/contracts/test_seedance_ark_video.py`
- **.test_generate_polls_and_downloads_without_extra_submission()** (6 connections) — `tests/contracts/test_seedance_ark_video.py`
- **fake_get()** (6 connections) — `tests/contracts/test_seedance_ark_video.py`
- **.test_local_first_frame_is_embedded_without_fal_upload()** (5 connections) — `tests/contracts/test_seedance_ark_video.py`
- **.test_query_retries_transient_server_error()** (4 connections) — `tests/contracts/test_seedance_ark_video.py`
- **.test_reference_media_roles_follow_official_contract()** (4 connections) — `tests/contracts/test_seedance_ark_video.py`
- **.test_valid_audio_data_uri_reaches_mocked_create()** (4 connections) — `tests/contracts/test_seedance_ark_video.py`
- **.test_custom_query_without_price_reports_unknown_not_zero()** (3 connections) — `tests/contracts/test_seedance_ark_video.py`
- **.test_cancel_uses_delete()** (3 connections) — `tests/contracts/test_seedance_ark_video.py`
- **.test_create_uses_official_endpoint_bearer_auth_and_body()** (3 connections) — `tests/contracts/test_seedance_ark_video.py`
- **.test_query_uses_get_and_returns_task_payload()** (3 connections) — `tests/contracts/test_seedance_ark_video.py`
- **fake_get()** (2 connections) — `tests/contracts/test_seedance_ark_video.py`
- **fake_post()** (2 connections) — `tests/contracts/test_seedance_ark_video.py`
- **fake_post()** (2 connections) — `tests/contracts/test_seedance_ark_video.py`
- **fake_get()** (2 connections) — `tests/contracts/test_seedance_ark_video.py`
- **fake_post()** (2 connections) — `tests/contracts/test_seedance_ark_video.py`
- **fake_get()** (2 connections) — `tests/contracts/test_seedance_ark_video.py`
- **fake_post()** (2 connections) — `tests/contracts/test_seedance_ark_video.py`
- **fake_post()** (2 connections) — `tests/contracts/test_seedance_ark_video.py`
- **fake_delete()** (2 connections) — `tests/contracts/test_seedance_ark_video.py`
- **fake_get()** (2 connections) — `tests/contracts/test_seedance_ark_video.py`
- *... and 5 more nodes in this community*

## Relationships

- [Seedance Video Provider](Seedance_Video_Provider.md) (12 shared connections)
- [Input Safety Testing](Input_Safety_Testing.md) (8 shared connections)
- [Core Utilities](Core_Utilities.md) (2 shared connections)
- [Cost Formula Tests](Cost_Formula_Tests.md) (1 shared connections)

## Source Files

- `tests/contracts/test_seedance_ark_video.py`

## Audit Trail

- EXTRACTED: 53 (78%)
- INFERRED: 15 (22%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*