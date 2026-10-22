# Schema Validation Tests

> 10 nodes · cohesion 0.20

## Key Concepts

- **TestSchemaValidation** (11 connections) — `tests/contracts/test_jimeng_video.py`
- **.test_frames_accepts_121()** (2 connections) — `tests/contracts/test_jimeng_video.py`
- **.test_frames_rejects_non_enum()** (2 connections) — `tests/contracts/test_jimeng_video.py`
- **.test_prompt_accepts_800_chars()** (2 connections) — `tests/contracts/test_jimeng_video.py`
- **.test_prompt_max_length_800()** (2 connections) — `tests/contracts/test_jimeng_video.py`
- **.test_prompt_rejects_over_800_chars()** (2 connections) — `tests/contracts/test_jimeng_video.py`
- **.test_seed_accepts_negative_one()** (2 connections) — `tests/contracts/test_jimeng_video.py`
- **.test_seed_accepts_zero_and_positive()** (2 connections) — `tests/contracts/test_jimeng_video.py`
- **.test_seed_minimum_is_negative_one()** (2 connections) — `tests/contracts/test_jimeng_video.py`
- **.test_seed_rejects_below_negative_one()** (2 connections) — `tests/contracts/test_jimeng_video.py`

## Relationships

- [Test Contract Validation](Test_Contract_Validation.md) (10 shared connections)
- [Tool Testing](Tool_Testing.md) (1 shared connections)

## Source Files

- `tests/contracts/test_jimeng_video.py`

## Audit Trail

- EXTRACTED: 19 (95%)
- INFERRED: 1 (5%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*