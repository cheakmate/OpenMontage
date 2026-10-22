# Wan Video Testing

> 20 nodes · cohesion 0.13

## Key Concepts

- **test_wan_video.py** (36 connections) — `tests/contracts/test_wan_video.py`
- **snap_frames()** (10 connections) — `tools/video/_wan_engine.py`
- **TestGeometry** (6 connections) — `tests/contracts/test_wan_video.py`
- **snap_dimension()** (6 connections) — `tools/video/_wan_engine.py`
- **parametrize** (5 connections)
- **.test_snap_dimension_aligns()** (3 connections) — `tests/contracts/test_wan_video.py`
- **.test_snap_frames_lands_on_a_latent_boundary()** (3 connections) — `tests/contracts/test_wan_video.py`
- **.test_long_request_is_clamped_to_one_pass()** (3 connections) — `tests/contracts/test_wan_video.py`
- **test_default_variant_covers_the_full_matrix()** (2 connections) — `tests/contracts/test_wan_video.py`
- **test_ti2v_is_the_only_32_aligned_line()** (2 connections) — `tests/contracts/test_wan_video.py`
- **test_wan21_1_3b_does_not_claim_image_to_video()** (2 connections) — `tests/contracts/test_wan_video.py`
- **.test_snap_dimension_never_returns_zero()** (2 connections) — `tests/contracts/test_wan_video.py`
- **.test_snap_frames_is_idempotent()** (2 connections) — `tests/contracts/test_wan_video.py`
- **.test_snap_frames_rejects_zero()** (2 connections) — `tests/contracts/test_wan_video.py`
- **Contract tests for the local Wan 2.x video tool. These run without a GPU,…** (1 connections) — `tests/contracts/test_wan_video.py`
- **Wan 2.1 never shipped 1.3B I2V weights; claiming it pulled a 14B model.** (1 connections) — `tests/contracts/test_wan_video.py`
- **The default must handle every operation the tool advertises.** (1 connections) — `tests/contracts/test_wan_video.py`
- **The 16x VAE plus 2x patching is what forces 1280x704 instead of 1280x720.** (1 connections) — `tests/contracts/test_wan_video.py`
- **Snap ``num_frames`` down onto the nearest valid ``temporal_scale * k + 1``.…** (1 connections) — `tools/video/_wan_engine.py`
- **Snap a width/height onto a multiple of the VAE spatial compression.** (1 connections) — `tools/video/_wan_engine.py`

## Relationships

- [WAN Model Validation](WAN_Model_Validation.md) (5 shared connections)
- [Tool Execution Cost Model](Tool_Execution_Cost_Model.md) (5 shared connections)
- [WAN Engine](WAN_Engine.md) (4 shared connections)
- [Tool Testing](Tool_Testing.md) (4 shared connections)
- [Core Utilities](Core_Utilities.md) (4 shared connections)
- [Video Continuation Chains](Video_Continuation_Chains.md) (3 shared connections)
- [Segment Planning Tests](Segment_Planning_Tests.md) (3 shared connections)
- [Tool Execution](Tool_Execution.md) (2 shared connections)
- [Allocator Diagnostics](Allocator_Diagnostics.md) (2 shared connections)
- [Offload Mode Selection](Offload_Mode_Selection.md) (2 shared connections)
- [Precision Selection Tests](Precision_Selection_Tests.md) (2 shared connections)
- [Variant Operation Validation](Variant_Operation_Validation.md) (2 shared connections)

## Source Files

- `tests/contracts/test_wan_video.py`
- `tools/video/_wan_engine.py`

## Audit Trail

- EXTRACTED: 65 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*