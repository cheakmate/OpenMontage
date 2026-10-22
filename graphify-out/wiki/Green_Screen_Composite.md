# Green Screen Composite

> 21 nodes · cohesion 0.16

## Key Concepts

- **GreenScreenComposite** (19 connections) — `tools/video/green_screen_composite.py`
- **.execute()** (10 connections) — `tools/video/green_screen_composite.py`
- **._probe_video()** (6 connections) — `tools/video/green_screen_composite.py`
- **._composite_frame()** (5 connections) — `tools/video/green_screen_composite.py`
- **._encode_frames()** (5 connections) — `tools/video/green_screen_composite.py`
- **._extract_frames()** (5 connections) — `tools/video/green_screen_composite.py`
- **._mux_audio()** (5 connections) — `tools/video/green_screen_composite.py`
- **Path** (5 connections)
- **._cleanup_temp()** (4 connections) — `tools/video/green_screen_composite.py`
- **._parse_hex_color()** (4 connections) — `tools/video/green_screen_composite.py`
- **Any** (3 connections)
- **.estimate_runtime()** (2 connections) — `tools/video/green_screen_composite.py`
- **ndarray** (2 connections)
- **Image** (1 connections)
- **Parse a hex color string like '#0E172A' to an RGB numpy array.** (1 connections) — `tools/video/green_screen_composite.py`
- **Probe a video for fps, duration, and dimensions.** (1 connections) — `tools/video/green_screen_composite.py`
- **Extract frames from a video at the given fps.** (1 connections) — `tools/video/green_screen_composite.py`
- **Composite a single speaker frame over a background frame using the given layout.** (1 connections) — `tools/video/green_screen_composite.py`
- **Encode PNG frames to an MP4 video.** (1 connections) — `tools/video/green_screen_composite.py`
- **Mux audio from the original source into the composite video.** (1 connections) — `tools/video/green_screen_composite.py`
- **Remove temporary frame directories.** (1 connections) — `tools/video/green_screen_composite.py`

## Relationships

- [Core Utilities](Core_Utilities.md) (6 shared connections)
- [FFmpeg Tests](FFmpeg_Tests.md) (4 shared connections)
- [Tool Testing](Tool_Testing.md) (3 shared connections)
- [Character Animation](Character_Animation.md) (2 shared connections)

## Source Files

- `tools/video/green_screen_composite.py`

## Audit Trail

- EXTRACTED: 41 (84%)
- INFERRED: 8 (16%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*