# Tool Status Reporting

> 55 nodes · cohesion 0.06

## Key Concepts

- **VideoAnalyzer** (29 connections) — `tools/analysis/video_analyzer.py`
- **Transcriber** (27 connections) — `tools/analysis/transcriber.py`
- **.execute()** (27 connections) — `tools/analysis/video_analyzer.py`
- **AudioEnergy** (17 connections) — `tools/analysis/audio_energy.py`
- **TranscriptFetcher** (14 connections) — `tools/analysis/transcript_fetcher.py`
- **TestPhase1ToolStatus** (11 connections) — `tests/contracts/test_phase1_contracts.py`
- **.execute()** (7 connections) — `tools/analysis/transcriber.py`
- **.execute()** (5 connections) — `tools/analysis/transcript_fetcher.py`
- **._get_duration()** (5 connections) — `tools/analysis/video_analyzer.py`
- **.test_transcriber_reports_status_correctly()** (4 connections) — `tests/contracts/test_phase1_contracts.py`
- **.execute()** (4 connections) — `tools/analysis/audio_energy.py`
- **._extract_video_id()** (4 connections) — `tools/analysis/transcript_fetcher.py`
- **._classify_scene_motion()** (4 connections) — `tools/analysis/video_analyzer.py`
- **._detect_platform()** (4 connections) — `tools/analysis/video_analyzer.py`
- **._is_url()** (4 connections) — `tools/analysis/video_analyzer.py`
- **._save_brief()** (4 connections) — `tools/analysis/video_analyzer.py`
- **.test_transcriber_missing_file()** (3 connections) — `tests/contracts/test_phase1_contracts.py`
- **._apply_diarization()** (3 connections) — `tools/analysis/transcriber.py`
- **.estimate_runtime()** (3 connections) — `tools/analysis/transcriber.py`
- **.get_status()** (3 connections) — `tools/analysis/transcriber.py`
- **._classify_pacing()** (3 connections) — `tools/analysis/video_analyzer.py`
- **._compute_keyframe_timestamps()** (3 connections) — `tools/analysis/video_analyzer.py`
- **._estimate_complexity()** (3 connections) — `tools/analysis/video_analyzer.py`
- **._needs_motion()** (3 connections) — `tools/analysis/video_analyzer.py`
- **._read_frame_at()** (3 connections) — `tools/analysis/video_analyzer.py`
- *... and 30 more nodes in this community*

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (46 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (8 shared connections)
- [Frame Sampler Tests](Frame_Sampler_Tests.md) (6 shared connections)
- [Value Matrix Transform](Value_Matrix_Transform.md) (3 shared connections)
- [Subtitle Generation Tests](Subtitle_Generation_Tests.md) (2 shared connections)
- [Enhancement Error Tests](Enhancement_Error_Tests.md) (2 shared connections)
- [Audio Mixer Tests](Audio_Mixer_Tests.md) (1 shared connections)
- [Cinematic Remotion Adapter](Cinematic_Remotion_Adapter.md) (1 shared connections)
- [Video Trimmer Tests](Video_Trimmer_Tests.md) (1 shared connections)
- [Video Download Pipeline](Video_Download_Pipeline.md) (1 shared connections)
- [Scene Detection](Scene_Detection.md) (1 shared connections)
- [Video Review Tooling](Video_Review_Tooling.md) (1 shared connections)

## Source Files

- `tests/contracts/test_phase1_contracts.py`
- `tools/analysis/audio_energy.py`
- `tools/analysis/transcriber.py`
- `tools/analysis/transcript_fetcher.py`
- `tools/analysis/video_analyzer.py`

## Audit Trail

- EXTRACTED: 102 (65%)
- INFERRED: 54 (35%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*