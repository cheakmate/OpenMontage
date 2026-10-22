# Offload Mode Selection

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

- [Wan Video Testing](Wan_Video_Testing.md) (2 shared connections)
- [WAN Model Validation](WAN_Model_Validation.md) (1 shared connections)
- [Precision Selection Tests](Precision_Selection_Tests.md) (1 shared connections)
- [Tool Execution Cost Model](Tool_Execution_Cost_Model.md) (1 shared connections)
- [Tool Testing](Tool_Testing.md) (1 shared connections)
- [WAN Engine](WAN_Engine.md) (1 shared connections)

## Source Files

- `tests/contracts/test_wan_video.py`
- `tools/video/_wan_engine.py`

## Audit Trail

- EXTRACTED: 19 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*