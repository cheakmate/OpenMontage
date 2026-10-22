# Silence Cutter

> 17 nodes · cohesion 0.19

## Key Concepts

- **SilenceCutter** (18 connections) — `tools/video/silence_cutter.py`
- **.execute()** (8 connections) — `tools/video/silence_cutter.py`
- **._render_speed_up()** (7 connections) — `tools/video/silence_cutter.py`
- **._render_jump_cut()** (6 connections) — `tools/video/silence_cutter.py`
- **._detect_silence()** (5 connections) — `tools/video/silence_cutter.py`
- **._get_duration()** (5 connections) — `tools/video/silence_cutter.py`
- **Path** (4 connections)
- **._build_atempo_chain()** (3 connections) — `tools/video/silence_cutter.py`
- **._compute_speech_segments()** (3 connections) — `tools/video/silence_cutter.py`
- **.estimate_runtime()** (2 connections) — `tools/video/silence_cutter.py`
- **Any** (2 connections)
- **Detect silent segments using FFmpeg silencedetect filter.** (1 connections) — `tools/video/silence_cutter.py`
- **Get video duration via ffprobe.** (1 connections) — `tools/video/silence_cutter.py`
- **Compute speech segments as the inverse of silence segments, with padding.** (1 connections) — `tools/video/silence_cutter.py`
- **Remove silence by concatenating speech segments.** (1 connections) — `tools/video/silence_cutter.py`
- **Speed up silent segments instead of removing them. This is less jarring than…** (1 connections) — `tools/video/silence_cutter.py`
- **Build atempo filter chain. atempo accepts [0.5, 100.0].** (1 connections) — `tools/video/silence_cutter.py`

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (9 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (4 shared connections)
- [Video Review Tooling](Video_Review_Tooling.md) (4 shared connections)

## Source Files

- `tools/video/silence_cutter.py`

## Audit Trail

- EXTRACTED: 35 (81%)
- INFERRED: 8 (19%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*