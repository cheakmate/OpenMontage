# Clip Preflight

> 44 nodes · cohesion 0.10

## Key Concepts

- **VideoStitch** (37 connections) — `tools/video/video_stitch.py`
- **._stitch()** (15 connections) — `tools/video/video_stitch.py`
- **Any** (15 connections)
- **._spatial()** (11 connections) — `tools/video/video_stitch.py`
- **Path** (10 connections)
- **.dry_run()** (8 connections) — `tools/video/video_stitch.py`
- **.execute()** (8 connections) — `tools/video/video_stitch.py`
- **._probe_clip()** (8 connections) — `tools/video/video_stitch.py`
- **._stitch_crossfade()** (8 connections) — `tools/video/video_stitch.py`
- **._stitch_fade_through_black()** (8 connections) — `tools/video/video_stitch.py`
- **._chain_xfade()** (7 connections) — `tools/video/video_stitch.py`
- **._ensure_audio_for_clips()** (7 connections) — `tools/video/video_stitch.py`
- **._preview_stitch()** (6 connections) — `tools/video/video_stitch.py`
- **._spatial_pip()** (6 connections) — `tools/video/video_stitch.py`
- **._stitch_cut()** (6 connections) — `tools/video/video_stitch.py`
- **._validate()** (6 connections) — `tools/video/video_stitch.py`
- **._cleanup_temp()** (5 connections) — `tools/video/video_stitch.py`
- **._get_xfade_offset()** (5 connections) — `tools/video/video_stitch.py`
- **._normalize_clip()** (5 connections) — `tools/video/video_stitch.py`
- **._resolve_normalization_target()** (5 connections) — `tools/video/video_stitch.py`
- **._spatial_side_by_side()** (5 connections) — `tools/video/video_stitch.py`
- **._spatial_vertical_stack()** (5 connections) — `tools/video/video_stitch.py`
- **._clip_has_audio()** (4 connections) — `tools/video/video_stitch.py`
- **._needs_normalization()** (4 connections) — `tools/video/video_stitch.py`
- **Preflight check: validate clips and report what would happen.** (1 connections) — `tools/video/video_stitch.py`
- *... and 19 more nodes in this community*

## Relationships

- [FFmpeg Tests](FFmpeg_Tests.md) (11 shared connections)
- [Core Utilities](Core_Utilities.md) (7 shared connections)
- [Character Animation](Character_Animation.md) (6 shared connections)
- [Video Stitch Jobs](Video_Stitch_Jobs.md) (5 shared connections)
- [Tool Testing](Tool_Testing.md) (3 shared connections)
- [Asset Cache Wrapper](Asset_Cache_Wrapper.md) (2 shared connections)
- [Image Selector](Image_Selector.md) (1 shared connections)
- [Media Profile Manager](Media_Profile_Manager.md) (1 shared connections)

## Source Files

- `tools/video/video_stitch.py`

## Audit Trail

- EXTRACTED: 119 (92%)
- INFERRED: 11 (8%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*