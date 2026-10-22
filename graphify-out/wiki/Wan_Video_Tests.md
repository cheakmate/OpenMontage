# Wan Video Tests

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

- [Tool Base Runtime](Tool_Base_Runtime.md) (9 shared connections)
- [Wan Pipeline Validation Tests](Wan_Pipeline_Validation_Tests.md) (5 shared connections)
- [Segment Cost Planning Tests](Segment_Cost_Planning_Tests.md) (5 shared connections)
- [Wan Video Engine](Wan_Video_Engine.md) (4 shared connections)
- [Video Chaining Operations](Video_Chaining_Operations.md) (3 shared connections)
- [Segment Planning Tests](Segment_Planning_Tests.md) (3 shared connections)
- [OOM Diagnostics](OOM_Diagnostics.md) (2 shared connections)
- [GPU Offload Selection](GPU_Offload_Selection.md) (2 shared connections)
- [Precision Selection](Precision_Selection.md) (2 shared connections)
- [Variant Catalog Tests](Variant_Catalog_Tests.md) (2 shared connections)
- [Tool Registry Discovery Tests](Tool_Registry_Discovery_Tests.md) (1 shared connections)
- [Project Init Validation](Project_Init_Validation.md) (1 shared connections)

## Source Files

- `tests/contracts/test_wan_video.py`
- `tools/video/_wan_engine.py`

## Audit Trail

- EXTRACTED: 65 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*