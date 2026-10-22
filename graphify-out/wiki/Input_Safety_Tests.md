# Input Safety Tests

> 28 nodes · cohesion 0.11

## Key Concepts

- **TestInputSafety** (21 connections) — `tests/contracts/test_seedance_ark_video.py`
- **fail_network()** (12 connections) — `tests/contracts/test_seedance_ark_video.py`
- **.test_non_finite_exchange_rate_never_reaches_paid_post()** (5 connections) — `tests/contracts/test_seedance_ark_video.py`
- **.test_non_finite_custom_price_never_reaches_paid_post()** (5 connections) — `tests/contracts/test_seedance_ark_video.py`
- **parametrize** (5 connections)
- **.test_corrupt_or_tiny_image_data_uri_never_reaches_network()** (4 connections) — `tests/contracts/test_seedance_ark_video.py`
- **.test_corrupt_or_tiny_local_image_never_reaches_network()** (4 connections) — `tests/contracts/test_seedance_ark_video.py`
- **.test_dry_run_is_offline_and_never_submits()** (4 connections) — `tests/contracts/test_seedance_ark_video.py`
- **.test_invalid_exchange_rate_fails_before_paid_post()** (4 connections) — `tests/contracts/test_seedance_ark_video.py`
- **.test_invalid_input_never_reaches_network()** (4 connections) — `tests/contracts/test_seedance_ark_video.py`
- **.test_non_finite_custom_price_never_returns_query_cost()** (4 connections) — `tests/contracts/test_seedance_ark_video.py`
- **.test_non_finite_exchange_rate_never_returns_query_cost()** (4 connections) — `tests/contracts/test_seedance_ark_video.py`
- **.test_rejects_bearer_prefix_before_network()** (4 connections) — `tests/contracts/test_seedance_ark_video.py`
- **.test_rejects_fast_1080p_before_network()** (4 connections) — `tests/contracts/test_seedance_ark_video.py`
- **.test_rejects_local_reference_video_before_network()** (4 connections) — `tests/contracts/test_seedance_ark_video.py`
- **.test_short_local_audio_never_reaches_network()** (4 connections) — `tests/contracts/test_seedance_ark_video.py`
- **.test_errors_redact_api_key()** (3 connections) — `tests/contracts/test_seedance_ark_video.py`
- **fail_network()** (1 connections) — `tests/contracts/test_seedance_ark_video.py`
- **fail_network()** (1 connections) — `tests/contracts/test_seedance_ark_video.py`
- **fail_network()** (1 connections) — `tests/contracts/test_seedance_ark_video.py`
- **failing_post()** (1 connections) — `tests/contracts/test_seedance_ark_video.py`
- **fail_network()** (1 connections) — `tests/contracts/test_seedance_ark_video.py`
- **fail_network()** (1 connections) — `tests/contracts/test_seedance_ark_video.py`
- **fail_network()** (1 connections) — `tests/contracts/test_seedance_ark_video.py`
- **fail_network()** (1 connections) — `tests/contracts/test_seedance_ark_video.py`
- *... and 3 more nodes in this community*

## Relationships

- [Seedance Ark Video](Seedance_Ark_Video.md) (15 shared connections)
- [Provider Resilience Tests](Provider_Resilience_Tests.md) (8 shared connections)
- [Cost Formula Tests](Cost_Formula_Tests.md) (2 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (1 shared connections)

## Source Files

- `tests/contracts/test_seedance_ark_video.py`

## Audit Trail

- EXTRACTED: 52 (79%)
- INFERRED: 14 (21%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*