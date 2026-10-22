# Precision Selection Tests

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

- [Wan Video Testing](Wan_Video_Testing.md) (2 shared connections)
- [WAN Engine](WAN_Engine.md) (2 shared connections)
- [WAN Model Validation](WAN_Model_Validation.md) (1 shared connections)
- [Tool Execution Cost Model](Tool_Execution_Cost_Model.md) (1 shared connections)
- [Tool Testing](Tool_Testing.md) (1 shared connections)
- [Offload Mode Selection](Offload_Mode_Selection.md) (1 shared connections)

## Source Files

- `tests/contracts/test_wan_video.py`
- `tools/video/_wan_engine.py`

## Audit Trail

- EXTRACTED: 18 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*