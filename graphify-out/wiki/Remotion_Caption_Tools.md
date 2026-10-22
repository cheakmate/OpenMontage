# Remotion Caption Tools

> 18 nodes · cohesion 0.17

## Key Concepts

- **RemotionCaptionBurn** (18 connections) — `tools/video/remotion_caption_burn.py`
- **.execute()** (8 connections) — `tools/video/remotion_caption_burn.py`
- **._render_ffmpeg()** (6 connections) — `tools/video/remotion_caption_burn.py`
- **._render_remotion()** (6 connections) — `tools/video/remotion_caption_burn.py`
- **test_remotion_video_src_is_relative_to_public_dir()** (5 connections) — `tests/tools/test_remotion_caption_burn.py`
- **._find_remotion_root()** (5 connections) — `tools/video/remotion_caption_burn.py`
- **._remotion_available()** (3 connections) — `tools/video/remotion_caption_burn.py`
- **._segments_to_word_captions()** (3 connections) — `tools/video/remotion_caption_burn.py`
- **._srt_to_word_captions()** (3 connections) — `tools/video/remotion_caption_burn.py`
- **._ms_to_srt()** (2 connections) — `tools/video/remotion_caption_burn.py`
- **fake_run_command()** (1 connections) — `tests/tools/test_remotion_caption_burn.py`
- **Any** (1 connections)
- **Path** (1 connections)
- **Remotion's staticFile() requires paths relative to ``public/``. This exercises…** (1 connections) — `tests/tools/test_remotion_caption_burn.py`
- **Find the remotion-composer directory relative to the repo.** (1 connections) — `tools/video/remotion_caption_burn.py`
- **Convert transcriber segments to [{word, startMs, endMs}, ...].** (1 connections) — `tools/video/remotion_caption_burn.py`
- **Parse SRT file into word captions.** (1 connections) — `tools/video/remotion_caption_burn.py`
- **Fall back to FFmpeg subtitle burning at bottom of frame.** (1 connections) — `tools/video/remotion_caption_burn.py`

## Relationships

- [Core Utilities](Core_Utilities.md) (5 shared connections)
- [Character Animation](Character_Animation.md) (4 shared connections)
- [Audio Mixing](Audio_Mixing.md) (2 shared connections)
- [Tool Testing](Tool_Testing.md) (2 shared connections)
- [FFmpeg Tests](FFmpeg_Tests.md) (2 shared connections)

## Source Files

- `tests/tools/test_remotion_caption_burn.py`
- `tools/video/remotion_caption_burn.py`

## Audit Trail

- EXTRACTED: 33 (80%)
- INFERRED: 8 (20%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*