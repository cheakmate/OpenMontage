# TokenHub Video Payload Tests

> 25 nodes · cohesion 0.10

## Key Concepts

- **TestToolSpecific** (24 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **._build_payload()** (11 connections) — `tools/video/hunyuan_cloud_video.py`
- **._encode_image()** (5 connections) — `tools/video/hunyuan_cloud_video.py`
- **.test_build_payload_i2v_base64_from_path()** (4 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **.test_build_payload_t2v_minimal()** (4 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **.test_build_payload_i2v_includes_image_url()** (3 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **.test_build_payload_t2v_custom_logo_add()** (3 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **.test_build_payload_t2v_omits_image()** (3 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **.test_build_payload_t2v_with_resolution_and_logo()** (3 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **.test_incompatible_model_operation_fails_before_submit()** (3 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **.test_default_logo_add_is_1()** (2 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **.test_default_operation_is_text_to_video()** (2 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **.test_default_poll_interval_is_5()** (2 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **.test_default_resolution_is_720p()** (2 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **.test_default_timeout_is_600()** (2 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **.test_encode_image_raises_on_missing()** (2 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **.test_encode_image_returns_base64()** (2 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **.test_i2v_both_url_and_path_fails()** (2 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **.test_i2v_without_image_fails()** (2 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **.test_no_keys_returns_error()** (2 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **parametrize** (1 connections)
- **Minimal T2V payload — only prompt is required by TokenHub.** (1 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **image_path should be base64-encoded into the image field.** (1 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **Build the request body for TokenHub video submit.** (1 connections) — `tools/video/hunyuan_cloud_video.py`
- **Read a local image file and return a base64-encoded string.** (1 connections) — `tools/video/hunyuan_cloud_video.py`

## Relationships

- [Tool Contract Tests](Tool_Contract_Tests.md) (18 shared connections)
- [Auth Header Tests](Auth_Header_Tests.md) (5 shared connections)
- [Error Redaction](Error_Redaction.md) (2 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (1 shared connections)

## Source Files

- `tests/contracts/test_hunyuan_cloud_video.py`
- `tools/video/hunyuan_cloud_video.py`

## Audit Trail

- EXTRACTED: 50 (88%)
- INFERRED: 7 (12%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*