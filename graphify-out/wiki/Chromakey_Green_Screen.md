# Chromakey Green Screen

> 26 nodes · cohesion 0.14

## Key Concepts

- **GreenScreenProcessor** (24 connections) — `tools/video/green_screen_processor.py`
- **.execute()** (10 connections) — `tools/video/green_screen_processor.py`
- **Path** (9 connections)
- **._auto_detect_method()** (8 connections) — `tools/video/green_screen_processor.py`
- **._probe_video()** (6 connections) — `tools/video/green_screen_processor.py`
- **._process_chromakey()** (6 connections) — `tools/video/green_screen_processor.py`
- **test_chromakey_filter_scales_background_to_frame()** (5 connections) — `tests/tools/test_green_screen_chromakey.py`
- **._cleanup_dir()** (5 connections) — `tools/video/green_screen_processor.py`
- **._detect_green_screen_histogram()** (5 connections) — `tools/video/green_screen_processor.py`
- **._extract_frames()** (5 connections) — `tools/video/green_screen_processor.py`
- **._reconstruct_video()** (5 connections) — `tools/video/green_screen_processor.py`
- **._test_chromakey_quality()** (5 connections) — `tools/video/green_screen_processor.py`
- **._process_rembg()** (4 connections) — `tools/video/green_screen_processor.py`
- **Any** (3 connections)
- **.estimate_runtime()** (2 connections) — `tools/video/green_screen_processor.py`
- **fake_run()** (1 connections) — `tests/tools/test_green_screen_chromakey.py`
- **Offline: the built filtergraph must not leave a 1x1 background.** (1 connections) — `tests/tools/test_green_screen_chromakey.py`
- **Probe video for duration, dimensions, and fps.** (1 connections) — `tools/video/green_screen_processor.py`
- **Analyze sample frames to decide between chromakey and rembg. Extracts 5 evenly-…** (1 connections) — `tools/video/green_screen_processor.py`
- **Analyze frames for dominant green or blue channel presence. Uses FFmpeg…** (1 connections) — `tools/video/green_screen_processor.py`
- **Run chromakey on a test frame and estimate quality percentage. Returns a score…** (1 connections) — `tools/video/green_screen_processor.py`
- **Extract frames from video at target fps.** (1 connections) — `tools/video/green_screen_processor.py`
- **Process frames using FFmpeg chromakey filter. Applies chromakey to remove…** (1 connections) — `tools/video/green_screen_processor.py`
- **Process frames using rembg AI segmentation. Removes background with…** (1 connections) — `tools/video/green_screen_processor.py`
- **Reconstruct video from processed frames using FFmpeg.** (1 connections) — `tools/video/green_screen_processor.py`
- *... and 1 more nodes in this community*

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (9 shared connections)
- [Video Review Tooling](Video_Review_Tooling.md) (7 shared connections)
- [Environment Loader](Environment_Loader.md) (3 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (2 shared connections)

## Source Files

- `tests/tools/test_green_screen_chromakey.py`
- `tools/video/green_screen_processor.py`

## Audit Trail

- EXTRACTED: 56 (84%)
- INFERRED: 11 (16%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*