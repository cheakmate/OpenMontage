# Precision Selection

> 8 nodes · cohesion 0.36

## Key Concepts

- **resolve_precision()** (11 connections) — `tools/video/_wan_engine.py`
- **TestPrecisionSelection** (5 connections) — `tests/contracts/test_wan_video.py`
- **_vram_gb()** (3 connections) — `tools/video/_wan_engine.py`
- **.test_auto_degrades_as_the_model_grows()** (2 connections) — `tests/contracts/test_wan_video.py`
- **.test_auto_on_a_big_card_stays_bf16()** (2 connections) — `tests/contracts/test_wan_video.py`
- **.test_cpu_never_asks_for_a_cuda_only_quantizer()** (2 connections) — `tests/contracts/test_wan_video.py`
- **.test_explicit_precision_is_respected()** (2 connections) — `tests/contracts/test_wan_video.py`
- **Pick a weight precision that fits the visible GPU. ``model_params_b`` is the…** (1 connections) — `tools/video/_wan_engine.py`

## Relationships

- [Wan Video Tests](Wan_Video_Tests.md) (2 shared connections)
- [Wan Video Engine](Wan_Video_Engine.md) (2 shared connections)
- [Wan Pipeline Validation Tests](Wan_Pipeline_Validation_Tests.md) (1 shared connections)
- [Segment Cost Planning Tests](Segment_Cost_Planning_Tests.md) (1 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (1 shared connections)
- [GPU Offload Selection](GPU_Offload_Selection.md) (1 shared connections)

## Source Files

- `tests/contracts/test_wan_video.py`
- `tools/video/_wan_engine.py`

## Audit Trail

- EXTRACTED: 18 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*