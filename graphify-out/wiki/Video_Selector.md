# Video Selector

> 58 nodes · cohesion 0.07

## Key Concepts

- **VideoSelector** (60 connections) — `tools/video/video_selector.py`
- **test_video_selector_routing.py** (25 connections) — `tests/tools/test_video_selector_routing.py`
- **_StubTool** (20 connections) — `tests/tools/test_video_selector_routing.py`
- **.execute()** (15 connections) — `tools/video/video_selector.py`
- **_ScoreStub** (13 connections) — `tests/tools/test_video_selector_routing.py`
- **._providers()** (10 connections) — `tools/video/video_selector.py`
- **test_ark_local_reference_routes_without_fal_upload()** (7 connections) — `tests/tools/test_video_selector_routing.py`
- **.estimate_cost()** (7 connections) — `tools/video/video_selector.py`
- **.fallback_tools_for()** (7 connections) — `tools/video/video_selector.py`
- **test_lower_ranked_same_provider_still_reachable_when_higher_unavailable()** (6 connections) — `tests/tools/test_video_selector_routing.py`
- **.test_video_selector_routes_to_hunyuan_cloud()** (5 connections) — `tests/contracts/test_hunyuan_cloud_video.py`
- **test_estimate_cost_uses_selected_provider()** (5 connections) — `tests/tools/test_video_selector_routing.py`
- **test_estimate_runtime_uses_selected_provider()** (5 connections) — `tests/tools/test_video_selector_routing.py`
- **test_preferred_provider_gap_is_configurable()** (5 connections) — `tests/tools/test_video_selector_routing.py`
- **test_preferred_provider_honored_when_within_gap()** (5 connections) — `tests/tools/test_video_selector_routing.py`
- **test_preferred_provider_ignored_when_drastically_worse()** (5 connections) — `tests/tools/test_video_selector_routing.py`
- **test_preferred_provider_not_in_rankings_falls_through()** (5 connections) — `tests/tools/test_video_selector_routing.py`
- **test_two_tools_sharing_provider_are_both_selectable()** (5 connections) — `tests/tools/test_video_selector_routing.py`
- **.estimate_runtime()** (5 connections) — `tools/video/video_selector.py`
- **._prepare_task_context()** (5 connections) — `tools/video/video_selector.py`
- **Any** (5 connections)
- **test_fallback_keeps_image_selector_for_text_to_video()** (4 connections) — `tests/tools/test_video_selector_routing.py`
- **._tool_context_payload()** (4 connections) — `tools/video/video_selector.py`
- **.fallback_tools()** (3 connections) — `tools/video/video_selector.py`
- **.provider_matrix()** (3 connections) — `tools/video/video_selector.py`
- *... and 33 more nodes in this community*

## Relationships

- [Video Tool Readiness](Video_Tool_Readiness.md) (18 shared connections)
- [Core Utilities](Core_Utilities.md) (8 shared connections)
- [Tool Execution](Tool_Execution.md) (7 shared connections)
- [Character Animation](Character_Animation.md) (6 shared connections)
- [Image Selector](Image_Selector.md) (3 shared connections)
- [MiniMax Video](MiniMax_Video.md) (3 shared connections)
- [Atlas Provider Tests](Atlas_Provider_Tests.md) (3 shared connections)
- [Tool Testing](Tool_Testing.md) (3 shared connections)
- [Atlas Media Smoke](Atlas_Media_Smoke.md) (2 shared connections)
- [Gemini Video Tests](Gemini_Video_Tests.md) (2 shared connections)
- [Atlas Tool Tests](Atlas_Tool_Tests.md) (2 shared connections)
- [Path Scoring](Path_Scoring.md) (2 shared connections)

## Source Files

- `tests/contracts/test_hunyuan_cloud_video.py`
- `tests/tools/test_video_selector_routing.py`
- `tools/video/video_selector.py`

## Audit Trail

- EXTRACTED: 156 (87%)
- INFERRED: 23 (13%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*