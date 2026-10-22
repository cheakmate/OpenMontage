# Frame Sampler Tests

> 15 nodes · cohesion 0.29

## Key Concepts

- **FrameSampler** (22 connections) — `tools/analysis/frame_sampler.py`
- **TestPhase1ErrorHandling** (11 connections) — `tests/contracts/test_phase1_contracts.py`
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

- [Tool Base Runtime](Tool_Base_Runtime.md) (10 shared connections)
- [Tool Status Reporting](Tool_Status_Reporting.md) (6 shared connections)
- [Video Review Tooling](Video_Review_Tooling.md) (4 shared connections)
- [Video Trimmer Tests](Video_Trimmer_Tests.md) (2 shared connections)
- [Audio Mixer Tests](Audio_Mixer_Tests.md) (2 shared connections)
- [Cinematic Remotion Adapter](Cinematic_Remotion_Adapter.md) (2 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (2 shared connections)

## Source Files

- `tests/contracts/test_phase1_contracts.py`
- `tools/analysis/frame_sampler.py`

## Audit Trail

- EXTRACTED: 43 (74%)
- INFERRED: 15 (26%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*