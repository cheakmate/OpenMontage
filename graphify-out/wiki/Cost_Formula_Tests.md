# Cost Formula Tests

> 13 nodes · cohesion 0.26

## Key Concepts

- **.estimate_cost_cny()** (12 connections) — `tools/video/seedance_ark.py`
- **TestOfficialCostFormula** (10 connections) — `tests/contracts/test_seedance_ark_video.py`
- **.estimate_token_usage()** (10 connections) — `tools/video/seedance_ark.py`
- **._resolve_model()** (8 connections) — `tools/video/seedance_ark.py`
- **.test_custom_endpoint_cost_is_unknown_not_standard_price()** (4 connections) — `tests/contracts/test_seedance_ark_video.py`
- **.test_custom_endpoint_requires_price_before_paid_post()** (4 connections) — `tests/contracts/test_seedance_ark_video.py`
- **.test_input_video_duration_uses_video_price()** (4 connections) — `tests/contracts/test_seedance_ark_video.py`
- **.test_missing_video_duration_uses_conservative_fifteen_seconds()** (4 connections) — `tests/contracts/test_seedance_ark_video.py`
- **.test_standard_720p_five_seconds_without_video()** (4 connections) — `tests/contracts/test_seedance_ark_video.py`
- **.test_custom_endpoint_accepts_explicit_price()** (3 connections) — `tests/contracts/test_seedance_ark_video.py`
- **.estimate_runtime()** (3 connections) — `tools/video/seedance_ark.py`
- **fail_network()** (1 connections) — `tests/contracts/test_seedance_ark_video.py`
- **Estimate billable completion tokens using Ark's published formula.** (1 connections) — `tools/video/seedance_ark.py`

## Relationships

- [Seedance Video Provider](Seedance_Video_Provider.md) (13 shared connections)
- [Ark Tool Operations](Ark_Tool_Operations.md) (11 shared connections)
- [Input Safety Testing](Input_Safety_Testing.md) (2 shared connections)
- [Core Utilities](Core_Utilities.md) (1 shared connections)
- [API Testing](API_Testing.md) (1 shared connections)

## Source Files

- `tests/contracts/test_seedance_ark_video.py`
- `tools/video/seedance_ark.py`

## Audit Trail

- EXTRACTED: 37 (77%)
- INFERRED: 11 (23%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*