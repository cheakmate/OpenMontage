# Error Redaction Tests

> 9 nodes · cohesion 0.25

## Key Concepts

- **.execute()** (7 connections) — `tools/video/jimeng_video.py`
- **._safe_error()** (5 connections) — `tools/video/jimeng_video.py`
- **.get_status()** (4 connections) — `tools/video/jimeng_video.py`
- **.test_safe_error_no_empty_string_bug()** (3 connections) — `tests/contracts/test_jimeng_video.py`
- **._ak()** (3 connections) — `tools/video/jimeng_video.py`
- **._sk()** (3 connections) — `tools/video/jimeng_video.py`
- **.test_safe_error_redacts_keys()** (2 connections) — `tests/contracts/test_jimeng_video.py`
- **Exception** (1 connections)
- **Regression: when no keys are set, _safe_error must not mangle.** (1 connections) — `tests/contracts/test_jimeng_video.py`

## Relationships

- [Tool Contract Tests](Tool_Contract_Tests.md) (5 shared connections)
- [Tool Defaults Tests](Tool_Defaults_Tests.md) (2 shared connections)
- [Signed Task Client](Signed_Task_Client.md) (2 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (1 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (1 shared connections)

## Source Files

- `tests/contracts/test_jimeng_video.py`
- `tools/video/jimeng_video.py`

## Audit Trail

- EXTRACTED: 20 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*