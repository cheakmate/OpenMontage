# API Code Validation Tests

> 14 nodes · cohesion 0.18

## Key Concepts

- **TestToolSpecific** (21 connections) — `tests/contracts/test_jimeng_video.py`
- **._check_code()** (8 connections) — `tools/video/jimeng_video.py`
- **.test_check_code_defaults_to_success_when_code_missing()** (3 connections) — `tests/contracts/test_jimeng_video.py`
- **.test_json_or_raise_raises_on_non_json()** (3 connections) — `tests/contracts/test_jimeng_video.py`
- **.test_check_code_passes_on_success()** (2 connections) — `tests/contracts/test_jimeng_video.py`
- **.test_check_code_raises_on_api_error()** (2 connections) — `tests/contracts/test_jimeng_video.py`
- **.test_check_code_raises_on_http_error()** (2 connections) — `tests/contracts/test_jimeng_video.py`
- **.test_default_aspect_ratio_is_16_9()** (2 connections) — `tests/contracts/test_jimeng_video.py`
- **.test_default_frames_is_121()** (2 connections) — `tests/contracts/test_jimeng_video.py`
- **.test_default_seed_is_negative_one()** (2 connections) — `tests/contracts/test_jimeng_video.py`
- **.test_i2v_without_image_fails()** (2 connections) — `tests/contracts/test_jimeng_video.py`
- **.test_no_keys_returns_error()** (2 connections) — `tests/contracts/test_jimeng_video.py`
- **json()** (1 connections) — `tests/contracts/test_jimeng_video.py`
- **If code field is absent on HTTP 2xx, default to 10000 (success).** (1 connections) — `tests/contracts/test_jimeng_video.py`

## Relationships

- [Cost and Runtime Tests](Cost_and_Runtime_Tests.md) (8 shared connections)
- [Test Contract Validation](Test_Contract_Validation.md) (7 shared connections)
- [Selector Duration Tests](Selector_Duration_Tests.md) (3 shared connections)
- [Safe Error Tests](Safe_Error_Tests.md) (2 shared connections)
- [Tool Testing](Tool_Testing.md) (1 shared connections)

## Source Files

- `tests/contracts/test_jimeng_video.py`
- `tools/video/jimeng_video.py`

## Audit Trail

- EXTRACTED: 36 (97%)
- INFERRED: 1 (3%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*