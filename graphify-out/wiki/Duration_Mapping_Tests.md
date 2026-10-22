# Duration Mapping Tests

> 10 nodes · cohesion 0.27

## Key Concepts

- **._build_payload()** (11 connections) — `tools/video/jimeng_video.py`
- **TestSelectorDurationMapping** (6 connections) — `tests/contracts/test_jimeng_video.py`
- **.test_build_payload_i2v_includes_image()** (3 connections) — `tests/contracts/test_jimeng_video.py`
- **.test_build_payload_t2v()** (3 connections) — `tests/contracts/test_jimeng_video.py`
- **.test_build_payload_t2v_omits_image()** (3 connections) — `tests/contracts/test_jimeng_video.py`
- **.test_duration_10_maps_to_241_frames()** (2 connections) — `tests/contracts/test_jimeng_video.py`
- **.test_duration_5_maps_to_121_frames()** (2 connections) — `tests/contracts/test_jimeng_video.py`
- **.test_duration_defaults_to_5_when_absent()** (2 connections) — `tests/contracts/test_jimeng_video.py`
- **.test_frames_takes_priority_over_duration()** (2 connections) — `tests/contracts/test_jimeng_video.py`
- **._duration_to_frames()** (2 connections) — `tools/video/jimeng_video.py`

## Relationships

- [Tool Contract Tests](Tool_Contract_Tests.md) (6 shared connections)
- [Tool Defaults Tests](Tool_Defaults_Tests.md) (3 shared connections)
- [Signed Task Client](Signed_Task_Client.md) (2 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (1 shared connections)

## Source Files

- `tests/contracts/test_jimeng_video.py`
- `tools/video/jimeng_video.py`

## Audit Trail

- EXTRACTED: 20 (83%)
- INFERRED: 4 (17%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*