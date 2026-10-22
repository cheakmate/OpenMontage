# Tool Status Checks

> 98 nodes · cohesion 0.03

## Key Concepts

- **VideoAnalyzer** (29 connections) — `tools/analysis/video_analyzer.py`
- **Transcriber** (27 connections) — `tools/analysis/transcriber.py`
- **.execute()** (27 connections) — `tools/analysis/video_analyzer.py`
- **FrameSampler** (22 connections) — `tools/analysis/frame_sampler.py`
- **SceneDetect** (22 connections) — `tools/analysis/scene_detect.py`
- **video_analyzer.py** (22 connections) — `tools/analysis/video_analyzer.py`
- **VideoDownloader** (19 connections) — `tools/analysis/video_downloader.py`
- **AudioEnergy** (17 connections) — `tools/analysis/audio_energy.py`
- **TranscriptFetcher** (14 connections) — `tools/analysis/transcript_fetcher.py`
- **TestPhase1ToolStatus** (11 connections) — `tests/contracts/test_phase1_contracts.py`
- **.execute()** (9 connections) — `tools/analysis/video_downloader.py`
- **.execute()** (8 connections) — `tools/analysis/scene_detect.py`
- **._detect_ffmpeg()** (7 connections) — `tools/analysis/scene_detect.py`
- **.execute()** (7 connections) — `tools/analysis/transcriber.py`
- **._download_video()** (6 connections) — `tools/analysis/video_downloader.py`
- **._find_downloaded()** (6 connections) — `tools/analysis/video_downloader.py`
- **test_scene_detect_lavfi_escape.py** (6 connections) — `tests/tools/test_scene_detect_lavfi_escape.py`
- **test_transcriber_device_selection.py** (6 connections) — `tests/tools/test_transcriber_device_selection.py`
- **._escape_lavfi_movie_path()** (5 connections) — `tools/analysis/scene_detect.py`
- **.execute()** (5 connections) — `tools/analysis/transcript_fetcher.py`
- **._get_duration()** (5 connections) — `tools/analysis/video_analyzer.py`
- **._download_subtitles()** (5 connections) — `tools/analysis/video_downloader.py`
- **SceneDetectEscapingTests** (4 connections) — `tests/tools/test_scene_detect_lavfi_escape.py`
- **.test_transcriber_reports_status_correctly()** (4 connections) — `tests/contracts/test_phase1_contracts.py`
- **test_transcriber_falls_back_when_cuda_fails_during_iteration()** (4 connections) — `tests/tools/test_transcriber_device_selection.py`
- *... and 73 more nodes in this community*

## Relationships

- [Core Utilities](Core_Utilities.md) (46 shared connections)
- [Tool Testing](Tool_Testing.md) (27 shared connections)
- [Character Animation](Character_Animation.md) (15 shared connections)
- [Frame Sampler Tests](Frame_Sampler_Tests.md) (9 shared connections)
- [Tool Execution](Tool_Execution.md) (6 shared connections)
- [FFmpeg Tests](FFmpeg_Tests.md) (5 shared connections)
- [Video Trimmer Tests](Video_Trimmer_Tests.md) (4 shared connections)
- [Phase Comparison](Phase_Comparison.md) (3 shared connections)
- [Subtitle Generation](Subtitle_Generation.md) (2 shared connections)
- [Lyria BGM Generation](Lyria_BGM_Generation.md) (2 shared connections)
- [Audio Mixer Tests](Audio_Mixer_Tests.md) (1 shared connections)
- [Video Composition](Video_Composition.md) (1 shared connections)

## Source Files

- `tests/contracts/test_phase1_contracts.py`
- `tests/contracts/test_phase2_contracts.py`
- `tests/tools/test_scene_detect_lavfi_escape.py`
- `tests/tools/test_transcriber_device_selection.py`
- `tools/analysis/audio_energy.py`
- `tools/analysis/frame_sampler.py`
- `tools/analysis/scene_detect.py`
- `tools/analysis/transcriber.py`
- `tools/analysis/transcript_fetcher.py`
- `tools/analysis/video_analyzer.py`
- `tools/analysis/video_downloader.py`

## Audit Trail

- EXTRACTED: 208 (73%)
- INFERRED: 77 (27%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*