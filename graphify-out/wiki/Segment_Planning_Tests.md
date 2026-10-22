# Segment Planning Tests

> 10 nodes · cohesion 0.27

## Key Concepts

- **plan_segments()** (11 connections) — `tools/video/_wan_engine.py`
- **TestSegmentPlanning** (5 connections) — `tests/contracts/test_wan_video.py`
- **.test_plan_covers_every_requested_length()** (4 connections) — `tests/contracts/test_wan_video.py`
- **.test_carry_accounts_for_the_duplicated_anchor_frame()** (3 connections) — `tests/contracts/test_wan_video.py`
- **.test_thirty_seconds_at_24fps()** (3 connections) — `tests/contracts/test_wan_video.py`
- **.test_single_segment_when_it_fits()** (2 connections) — `tests/contracts/test_wan_video.py`
- **Segments must always reach the target; the tail is trimmed, never short. Swept…** (1 connections) — `tests/contracts/test_wan_video.py`
- **Each continuation reproduces the anchor, so it adds segment-1 frames.** (1 connections) — `tests/contracts/test_wan_video.py`
- **The headline case: 30s of 24fps video off a 121-frame model.** (1 connections) — `tests/contracts/test_wan_video.py`
- **Number of chained segments needed to cover ``total_frames``. The first segment…** (1 connections) — `tools/video/_wan_engine.py`

## Relationships

- [Wan Video Tests](Wan_Video_Tests.md) (3 shared connections)
- [Wan Pipeline Validation Tests](Wan_Pipeline_Validation_Tests.md) (1 shared connections)
- [Scene Pacing Verification](Scene_Pacing_Verification.md) (1 shared connections)
- [Segment Cost Planning Tests](Segment_Cost_Planning_Tests.md) (1 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (1 shared connections)
- [Wan Video Engine](Wan_Video_Engine.md) (1 shared connections)

## Source Files

- `tests/contracts/test_wan_video.py`
- `tools/video/_wan_engine.py`

## Audit Trail

- EXTRACTED: 20 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*