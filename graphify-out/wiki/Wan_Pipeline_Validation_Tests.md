# Wan Pipeline Validation Tests

> 15 nodes · cohesion 0.16

## Key Concepts

- **generate_wan()** (22 connections) — `tools/video/_wan_engine.py`
- **TestValidation** (7 connections) — `tests/contracts/test_wan_video.py`
- **_generate()** (5 connections) — `tests/contracts/test_wan_video.py`
- **export_frames()** (4 connections) — `tools/video/_wan_engine.py`
- **.test_operation_unsupported_by_variant_is_rejected()** (3 connections) — `tests/contracts/test_wan_video.py`
- **pipeline_scales()** (3 connections) — `tools/video/_wan_engine.py`
- **.test_missing_prompt_is_rejected()** (2 connections) — `tests/contracts/test_wan_video.py`
- **.test_unavailable_tool_reports_install_instructions()** (2 connections) — `tests/contracts/test_wan_video.py`
- **.test_unknown_operation_is_rejected()** (2 connections) — `tests/contracts/test_wan_video.py`
- **.test_unknown_variant_is_rejected()** (2 connections) — `tests/contracts/test_wan_video.py`
- **Path** (1 connections)
- **wan2.1-1.3b has no I2V weights — this must fail fast, not load 14B.** (1 connections) — `tests/contracts/test_wan_video.py`
- **Read (temporal, spatial) VAE compression factors off a loaded pipeline.** (1 connections) — `tools/video/_wan_engine.py`
- **Encode PIL frames to an H.264 MP4 that plays everywhere.** (1 connections) — `tools/video/_wan_engine.py`
- **Generate with a local Wan model, chaining segments for long durations.** (1 connections) — `tools/video/_wan_engine.py`

## Relationships

- [Wan Video Engine](Wan_Video_Engine.md) (7 shared connections)
- [Wan Video Tests](Wan_Video_Tests.md) (5 shared connections)
- [Segment Cost Planning Tests](Segment_Cost_Planning_Tests.md) (3 shared connections)
- [Video Chaining Operations](Video_Chaining_Operations.md) (1 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (1 shared connections)
- [Precision Selection](Precision_Selection.md) (1 shared connections)
- [GPU Offload Selection](GPU_Offload_Selection.md) (1 shared connections)
- [Segment Planning Tests](Segment_Planning_Tests.md) (1 shared connections)
- [OOM Diagnostics](OOM_Diagnostics.md) (1 shared connections)
- [CogVideo Variant Tests](CogVideo_Variant_Tests.md) (1 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (1 shared connections)

## Source Files

- `tests/contracts/test_wan_video.py`
- `tools/video/_wan_engine.py`

## Audit Trail

- EXTRACTED: 39 (98%)
- INFERRED: 1 (2%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*