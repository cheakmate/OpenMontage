# Signed Task Client

> 13 nodes · cohesion 0.22

## Key Concepts

- **._generate()** (9 connections) — `tools/video/jimeng_video.py`
- **Any** (8 connections)
- **._json_or_raise()** (6 connections) — `tools/video/jimeng_video.py`
- **._submit_task()** (6 connections) — `tools/video/jimeng_video.py`
- **._poll_task()** (5 connections) — `tools/video/jimeng_video.py`
- **._sign()** (5 connections) — `tools/video/jimeng_video.py`
- **.estimate_cost()** (4 connections) — `tools/video/jimeng_video.py`
- **.test_cost_scales_with_frames()** (3 connections) — `tests/contracts/test_jimeng_video.py`
- **.test_json_or_raise_returns_dict()** (3 connections) — `tests/contracts/test_jimeng_video.py`
- **.test_sign_includes_content_type()** (2 connections) — `tests/contracts/test_jimeng_video.py`
- **.test_sign_returns_authorization_header()** (2 connections) — `tests/contracts/test_jimeng_video.py`
- **.estimate_runtime()** (2 connections) — `tools/video/jimeng_video.py`
- **json()** (1 connections) — `tests/contracts/test_jimeng_video.py`

## Relationships

- [Tool Contract Tests](Tool_Contract_Tests.md) (8 shared connections)
- [Tool Defaults Tests](Tool_Defaults_Tests.md) (8 shared connections)
- [Error Redaction Tests](Error_Redaction_Tests.md) (2 shared connections)
- [Duration Mapping Tests](Duration_Mapping_Tests.md) (2 shared connections)
- [CogVideo Variant Tests](CogVideo_Variant_Tests.md) (1 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (1 shared connections)

## Source Files

- `tests/contracts/test_jimeng_video.py`
- `tools/video/jimeng_video.py`

## Audit Trail

- EXTRACTED: 38 (97%)
- INFERRED: 1 (3%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*