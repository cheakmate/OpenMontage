# Safe Error Tests

> 5 nodes · cohesion 0.40

## Key Concepts

- **._safe_error()** (6 connections) — `tools/video/hunyuan_cloud_video.py`
- **.test_safe_error_no_empty_string_bug()** (2 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **.test_safe_error_redacts_keys()** (2 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **Exception** (1 connections)
- **Redact secret values from exception messages.** (1 connections) — `tools/video/hunyuan_cloud_video.py`

## Relationships

- [Text-to-Video Testing](Text-to-Video_Testing.md) (2 shared connections)
- [Auth Header Testing](Auth_Header_Testing.md) (1 shared connections)
- [Tool Contract Tests](Tool_Contract_Tests.md) (1 shared connections)

## Source Files

- `tests/contracts/test_hunyuan_cloud_video.py`
- `tools/video/hunyuan_cloud_video.py`

## Audit Trail

- EXTRACTED: 8 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*