# Tool Execution Cost Model

> 28 nodes · cohesion 0.13

## Key Concepts

- **WanVideo** (35 connections) — `tools/video/wan_video.py`
- **TestContract** (15 connections) — `tests/contracts/test_wan_video.py`
- **._plan()** (8 connections) — `tools/video/wan_video.py`
- **TestPlan** (7 connections) — `tests/contracts/test_wan_video.py`
- **.estimate_runtime()** (7 connections) — `tools/video/wan_video.py`
- **TestRuntimeEstimate** (5 connections) — `tests/contracts/test_wan_video.py`
- **.execute()** (5 connections) — `tools/video/wan_video.py`
- **.test_scales_with_segment_count()** (4 connections) — `tests/contracts/test_wan_video.py`
- **.get_status()** (4 connections) — `tools/video/wan_video.py`
- **Any** (4 connections)
- **.test_longer_request_estimates_longer_runtime()** (3 connections) — `tests/contracts/test_wan_video.py`
- **.test_matches_measured_704x480_run()** (3 connections) — `tests/contracts/test_wan_video.py`
- **.test_sequential_costs_more_than_resident()** (3 connections) — `tests/contracts/test_wan_video.py`
- **.test_identity()** (2 connections) — `tests/contracts/test_wan_video.py`
- **.test_input_schema()** (2 connections) — `tests/contracts/test_wan_video.py`
- **.test_local_generation_is_free()** (2 connections) — `tests/contracts/test_wan_video.py`
- **.test_schema_operations_match_engine()** (2 connections) — `tests/contracts/test_wan_video.py`
- **.test_status_requires_opt_in()** (2 connections) — `tests/contracts/test_wan_video.py`
- **.test_duration_drives_segment_count()** (2 connections) — `tests/contracts/test_wan_video.py`
- **.test_explicit_num_frames_overrides_duration()** (2 connections) — `tests/contracts/test_wan_video.py`
- **.test_native_length_needs_one_segment()** (2 connections) — `tests/contracts/test_wan_video.py`
- **.test_text_to_image_is_a_single_frame()** (2 connections) — `tests/contracts/test_wan_video.py`
- **.estimate_cost()** (2 connections) — `tools/video/wan_video.py`
- **.test_inherits_base_tool()** (1 connections) — `tests/contracts/test_wan_video.py`
- **Each chained segment pays the full per-step cost again.** (1 connections) — `tests/contracts/test_wan_video.py`
- *... and 3 more nodes in this community*

## Relationships

- [Core Utilities](Core_Utilities.md) (7 shared connections)
- [Tool Testing](Tool_Testing.md) (7 shared connections)
- [Wan Video Testing](Wan_Video_Testing.md) (5 shared connections)
- [Tool Execution](Tool_Execution.md) (3 shared connections)
- [WAN Model Validation](WAN_Model_Validation.md) (3 shared connections)
- [Character Animation](Character_Animation.md) (2 shared connections)
- [Atlas Tool Tests](Atlas_Tool_Tests.md) (1 shared connections)
- [Tool Registry](Tool_Registry.md) (1 shared connections)
- [Precision Selection Tests](Precision_Selection_Tests.md) (1 shared connections)
- [Offload Mode Selection](Offload_Mode_Selection.md) (1 shared connections)
- [Segment Planning Tests](Segment_Planning_Tests.md) (1 shared connections)

## Source Files

- `tests/contracts/test_wan_video.py`
- `tools/video/wan_video.py`

## Audit Trail

- EXTRACTED: 58 (72%)
- INFERRED: 22 (28%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*