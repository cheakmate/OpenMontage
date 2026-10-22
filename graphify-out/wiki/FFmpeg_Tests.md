# FFmpeg Tests

> 35 nodes · cohesion 0.10

## Key Concepts

- **.run_command()** (77 connections) — `tools/base_tool.py`
- **GreenScreenProcessor** (24 connections) — `tools/video/green_screen_processor.py`
- **.execute()** (10 connections) — `tools/video/green_screen_processor.py`
- **Path** (9 connections)
- **._auto_detect_method()** (8 connections) — `tools/video/green_screen_processor.py`
- **._probe_video()** (6 connections) — `tools/video/green_screen_processor.py`
- **._process_chromakey()** (6 connections) — `tools/video/green_screen_processor.py`
- **ToolCommandError** (5 connections) — `tools/base_tool.py`
- **test_chromakey_filter_scales_background_to_frame()** (5 connections) — `tests/tools/test_green_screen_chromakey.py`
- **._cleanup_dir()** (5 connections) — `tools/video/green_screen_processor.py`
- **._detect_green_screen_histogram()** (5 connections) — `tools/video/green_screen_processor.py`
- **._extract_frames()** (5 connections) — `tools/video/green_screen_processor.py`
- **._reconstruct_video()** (5 connections) — `tools/video/green_screen_processor.py`
- **._test_chromakey_quality()** (5 connections) — `tools/video/green_screen_processor.py`
- **._detect_ffmpeg_simple()** (4 connections) — `tools/analysis/scene_detect.py`
- **._process_rembg()** (4 connections) — `tools/video/green_screen_processor.py`
- **Any** (3 connections)
- **.estimate_runtime()** (2 connections) — `tools/video/green_screen_processor.py`
- **fake_run()** (1 connections) — `tests/tools/test_green_screen_chromakey.py`
- **.__init__()** (1 connections) — `tools/base_tool.py`
- **.__str__()** (1 connections) — `tools/base_tool.py`
- **CompletedProcess** (1 connections)
- **Offline: the built filtergraph must not leave a 1x1 background.** (1 connections) — `tests/tools/test_green_screen_chromakey.py`
- **Simplest fallback: split into uniform segments.** (1 connections) — `tools/analysis/scene_detect.py`
- **Run a subprocess command with standard error handling. On Windows, resolves…** (1 connections) — `tools/base_tool.py`
- *... and 10 more nodes in this community*

## Relationships

- [Clip Preflight](Clip_Preflight.md) (11 shared connections)
- [Core Utilities](Core_Utilities.md) (10 shared connections)
- [Video Composition](Video_Composition.md) (7 shared connections)
- [Audio Mixer Tests](Audio_Mixer_Tests.md) (6 shared connections)
- [Tool Status Checks](Tool_Status_Checks.md) (5 shared connections)
- [Character Animation](Character_Animation.md) (4 shared connections)
- [Frame Sampler Tests](Frame_Sampler_Tests.md) (4 shared connections)
- [Visual QA Tool](Visual_QA_Tool.md) (4 shared connections)
- [Green Screen Composite](Green_Screen_Composite.md) (4 shared connections)
- [Silence Cutter](Silence_Cutter.md) (4 shared connections)
- [Tool Testing](Tool_Testing.md) (3 shared connections)
- [Phase Comparison](Phase_Comparison.md) (3 shared connections)

## Source Files

- `tests/tools/test_green_screen_chromakey.py`
- `tools/analysis/scene_detect.py`
- `tools/base_tool.py`
- `tools/video/green_screen_processor.py`

## Audit Trail

- EXTRACTED: 133 (92%)
- INFERRED: 11 (8%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*