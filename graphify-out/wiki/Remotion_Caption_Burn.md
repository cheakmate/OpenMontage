# Remotion Caption Burn

> 20 nodes · cohesion 0.15

## Key Concepts

- **RemotionCaptionBurn** (18 connections) — `tools/video/remotion_caption_burn.py`
- **.execute()** (8 connections) — `tools/video/remotion_caption_burn.py`
- **._render_ffmpeg()** (6 connections) — `tools/video/remotion_caption_burn.py`
- **._render_remotion()** (6 connections) — `tools/video/remotion_caption_burn.py`
- **test_remotion_caption_burn.py** (6 connections) — `tests/tools/test_remotion_caption_burn.py`
- **test_remotion_video_src_is_relative_to_public_dir()** (5 connections) — `tests/tools/test_remotion_caption_burn.py`
- **._find_remotion_root()** (5 connections) — `tools/video/remotion_caption_burn.py`
- **._remotion_available()** (3 connections) — `tools/video/remotion_caption_burn.py`
- **._segments_to_word_captions()** (3 connections) — `tools/video/remotion_caption_burn.py`
- **._srt_to_word_captions()** (3 connections) — `tools/video/remotion_caption_burn.py`
- **._ms_to_srt()** (2 connections) — `tools/video/remotion_caption_burn.py`
- **fake_run_command()** (1 connections) — `tests/tools/test_remotion_caption_burn.py`
- **Any** (1 connections)
- **Path** (1 connections)
- **Regression tests for Remotion talking-head caption prop generation.** (1 connections) — `tests/tools/test_remotion_caption_burn.py`
- **Remotion's staticFile() requires paths relative to ``public/``. This exercises…** (1 connections) — `tests/tools/test_remotion_caption_burn.py`
- **Find the remotion-composer directory relative to the repo.** (1 connections) — `tools/video/remotion_caption_burn.py`
- **Convert transcriber segments to [{word, startMs, endMs}, ...].** (1 connections) — `tools/video/remotion_caption_burn.py`
- **Parse SRT file into word captions.** (1 connections) — `tools/video/remotion_caption_burn.py`
- **Fall back to FFmpeg subtitle burning at bottom of frame.** (1 connections) — `tools/video/remotion_caption_burn.py`

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (9 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (4 shared connections)
- [Video Review Tooling](Video_Review_Tooling.md) (2 shared connections)
- [Environment Loader](Environment_Loader.md) (1 shared connections)

## Source Files

- `tests/tools/test_remotion_caption_burn.py`
- `tools/video/remotion_caption_burn.py`

## Audit Trail

- EXTRACTED: 37 (82%)
- INFERRED: 8 (18%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*