# Seedream Image Tests

> 49 nodes · cohesion 0.08

## Key Concepts

- **test_seedream_image.py** (21 connections) — `tests/tools/test_seedream_image.py`
- **.execute()** (17 connections) — `tools/graphics/seedream_image.py`
- **_setup_mock_execution()** (15 connections) — `tests/tools/test_seedream_image.py`
- **_FakeResponse** (10 connections) — `tests/tools/test_seedream_image.py`
- **.estimate_cost()** (10 connections) — `tools/graphics/seedream_image.py`
- **TestValidation** (8 connections) — `tests/tools/test_seedream_image.py`
- **TestCostEstimation** (6 connections) — `tests/tools/test_seedream_image.py`
- **TestMetadata** (5 connections) — `tests/tools/test_seedream_image.py`
- **_build_status_response()** (5 connections) — `tests/tools/test_seedream_image.py`
- **_build_submit_response()** (5 connections) — `tests/tools/test_seedream_image.py`
- **.test_completed_without_images_raises_error()** (5 connections) — `tests/tools/test_seedream_image.py`
- **parametrize** (5 connections)
- **TestAsyncPolling** (4 connections) — `tests/tools/test_seedream_image.py`
- **.test_failed_states_return_error()** (4 connections) — `tests/tools/test_seedream_image.py`
- **.test_timeout_returns_error()** (4 connections) — `tests/tools/test_seedream_image.py`
- **.test_cost_matches_estimate()** (4 connections) — `tests/tools/test_seedream_image.py`
- **.test_image_selector_routes_count_and_returns_distinct_artifacts()** (4 connections) — `tests/tools/test_seedream_image.py`
- **.test_artifacts_match_billed_count()** (4 connections) — `tests/tools/test_seedream_image.py`
- **.get_status()** (4 connections) — `tools/graphics/seedream_image.py`
- **TestMultiOutputRegression** (3 connections) — `tests/tools/test_seedream_image.py`
- **seedream_tool()** (3 connections) — `tests/tools/test_seedream_image.py`
- **_build_result_response()** (3 connections) — `tests/tools/test_seedream_image.py`
- **.test_completed_on_first_poll()** (3 connections) — `tests/tools/test_seedream_image.py`
- **.test_cost_scales_with_num_images()** (3 connections) — `tests/tools/test_seedream_image.py`
- **.test_large_size_pricing()** (3 connections) — `tests/tools/test_seedream_image.py`
- *... and 24 more nodes in this community*

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (12 shared connections)
- [Image Selector Tests](Image_Selector_Tests.md) (4 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (1 shared connections)
- [Lyria BGM Generator](Lyria_BGM_Generator.md) (1 shared connections)
- [Project Init Validation](Project_Init_Validation.md) (1 shared connections)
- [Tool Dependency Tests](Tool_Dependency_Tests.md) (1 shared connections)

## Source Files

- `tests/tools/test_seedream_image.py`
- `tools/graphics/seedream_image.py`

## Audit Trail

- EXTRACTED: 91 (80%)
- INFERRED: 23 (20%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*