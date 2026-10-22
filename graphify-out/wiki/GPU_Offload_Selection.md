# GPU Offload Selection

> 9 nodes · cohesion 0.33

## Key Concepts

- **resolve_offload_mode()** (12 connections) — `tools/video/_wan_engine.py`
- **TestOffloadSelection** (6 connections) — `tests/contracts/test_wan_video.py`
- **.test_bf16_5b_on_a_12gb_card_goes_sequential()** (3 connections) — `tests/contracts/test_wan_video.py`
- **.test_big_card_keeps_weights_resident()** (2 connections) — `tests/contracts/test_wan_video.py`
- **.test_cpu_only_does_not_ask_for_sequential()** (2 connections) — `tests/contracts/test_wan_video.py`
- **.test_explicit_mode_is_respected()** (2 connections) — `tests/contracts/test_wan_video.py`
- **.test_quantized_weights_fit_resident_on_the_same_card()** (2 connections) — `tests/contracts/test_wan_video.py`
- **10GB of resident bf16 weights leaves no room for activations.** (1 connections) — `tests/contracts/test_wan_video.py`
- **Choose how aggressively to offload weights to host RAM. ``model`` keeps a whole…** (1 connections) — `tools/video/_wan_engine.py`

## Relationships

- [Wan Video Tests](Wan_Video_Tests.md) (2 shared connections)
- [Wan Pipeline Validation Tests](Wan_Pipeline_Validation_Tests.md) (1 shared connections)
- [Precision Selection](Precision_Selection.md) (1 shared connections)
- [Segment Cost Planning Tests](Segment_Cost_Planning_Tests.md) (1 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (1 shared connections)
- [Wan Video Engine](Wan_Video_Engine.md) (1 shared connections)

## Source Files

- `tests/contracts/test_wan_video.py`
- `tools/video/_wan_engine.py`

## Audit Trail

- EXTRACTED: 19 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*