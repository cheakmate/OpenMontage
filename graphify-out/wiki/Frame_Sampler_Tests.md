# Frame Sampler Tests

> 13 nodes · cohesion 0.26

## Key Concepts

- **.execute()** (9 connections) — `tools/analysis/frame_sampler.py`
- **._extract_count()** (7 connections) — `tools/analysis/frame_sampler.py`
- **._extract_scene_guided()** (6 connections) — `tools/analysis/frame_sampler.py`
- **Path** (6 connections)
- **._collect_frames()** (5 connections) — `tools/analysis/frame_sampler.py`
- **._extract_interval()** (5 connections) — `tools/analysis/frame_sampler.py`
- **._extract_timestamps()** (5 connections) — `tools/analysis/frame_sampler.py`
- **._get_duration()** (5 connections) — `tools/analysis/frame_sampler.py`
- **.test_frame_sampler_missing_file()** (3 connections) — `tests/contracts/test_phase1_contracts.py`
- **Any** (1 connections)
- **Extract keyframes guided by scene boundaries. Extracts the first frame of each…** (1 connections) — `tools/analysis/frame_sampler.py`
- **Get video duration in seconds via ffprobe.** (1 connections) — `tools/analysis/frame_sampler.py`
- **Collect extracted frame files and build metadata.** (1 connections) — `tools/analysis/frame_sampler.py`

## Relationships

- [Tool Status Checks](Tool_Status_Checks.md) (9 shared connections)
- [FFmpeg Tests](FFmpeg_Tests.md) (4 shared connections)
- [Video Trimmer Tests](Video_Trimmer_Tests.md) (1 shared connections)
- [Character Animation](Character_Animation.md) (1 shared connections)

## Source Files

- `tests/contracts/test_phase1_contracts.py`
- `tools/analysis/frame_sampler.py`

## Audit Trail

- EXTRACTED: 33 (94%)
- INFERRED: 2 (6%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*