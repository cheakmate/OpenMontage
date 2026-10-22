# OOM Diagnostics

> 9 nodes · cohesion 0.31

## Key Concepts

- **_oom_aware_error()** (11 connections) — `tools/video/_wan_engine.py`
- **TestAllocatorDiagnostics** (5 connections) — `tests/contracts/test_wan_video.py`
- **.test_nvml_assert_is_reported_as_a_driver_mismatch()** (3 connections) — `tests/contracts/test_wan_video.py`
- **.test_oom_already_sequential_does_not_suggest_it_again()** (2 connections) — `tests/contracts/test_wan_video.py`
- **.test_real_oom_suggests_sequential_offload_first()** (2 connections) — `tests/contracts/test_wan_video.py`
- **.test_unrelated_failure_is_passed_through()** (2 connections) — `tests/contracts/test_wan_video.py`
- **Exception** (1 connections)
- **PyTorch calls NVML while reporting OOM, so a driver mismatch masks it.** (1 connections) — `tests/contracts/test_wan_video.py`
- **Turn an allocator failure into advice the caller can act on.** (1 connections) — `tools/video/_wan_engine.py`

## Relationships

- [Wan Video Tests](Wan_Video_Tests.md) (2 shared connections)
- [Wan Video Engine](Wan_Video_Engine.md) (2 shared connections)
- [Wan Pipeline Validation Tests](Wan_Pipeline_Validation_Tests.md) (1 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (1 shared connections)

## Source Files

- `tests/contracts/test_wan_video.py`
- `tools/video/_wan_engine.py`

## Audit Trail

- EXTRACTED: 17 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*