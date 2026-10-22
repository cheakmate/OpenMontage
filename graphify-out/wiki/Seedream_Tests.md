# Seedream Tests

> 48 nodes · cohesion 0.08

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
- **.test_artifacts_match_billed_count()** (4 connections) — `tests/tools/test_seedream_image.py`
- **.get_status()** (4 connections) — `tools/graphics/seedream_image.py`
- **TestMultiOutputRegression** (3 connections) — `tests/tools/test_seedream_image.py`
- **seedream_tool()** (3 connections) — `tests/tools/test_seedream_image.py`
- **_build_result_response()** (3 connections) — `tests/tools/test_seedream_image.py`
- **.test_completed_on_first_poll()** (3 connections) — `tests/tools/test_seedream_image.py`
- **.test_cost_scales_with_num_images()** (3 connections) — `tests/tools/test_seedream_image.py`
- **.test_large_size_pricing()** (3 connections) — `tests/tools/test_seedream_image.py`
- **.test_small_size_pricing()** (3 connections) — `tests/tools/test_seedream_image.py`
- *... and 23 more nodes in this community*

## Relationships

- [Tool Testing](Tool_Testing.md) (10 shared connections)
- [Image Selector](Image_Selector.md) (4 shared connections)
- [Character Animation](Character_Animation.md) (1 shared connections)
- [Tool Execution](Tool_Execution.md) (1 shared connections)
- [Lyria BGM Generation](Lyria_BGM_Generation.md) (1 shared connections)
- [Project Init](Project_Init.md) (1 shared connections)
- [Core Utilities](Core_Utilities.md) (1 shared connections)
- [Visual Evaluation System](Visual_Evaluation_System.md) (1 shared connections)

## Source Files

- `tests/tools/test_seedream_image.py`
- `tools/graphics/seedream_image.py`

## Audit Trail

- EXTRACTED: 90 (80%)
- INFERRED: 22 (20%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*