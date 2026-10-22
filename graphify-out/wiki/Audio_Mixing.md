# Audio Mixing

> 59 nodes · cohesion 0.06

## Key Concepts

- **subprocess** (101 connections)
- **cap_recorder.py** (25 connections) — `tools/capture/cap_recorder.py`
- **audio_mixer.py** (23 connections) — `tools/audio/audio_mixer.py`
- **screen_recorder.py** (20 connections) — `tools/capture/screen_recorder.py`
- **CapRecorder** (17 connections) — `tools/capture/cap_recorder.py`
- **ScreenRecorder** (15 connections) — `tools/capture/screen_recorder.py`
- **test_04_audio_mix.py** (11 connections) — `tests/qa/test_04_audio_mix.py`
- **test_audio_mixer_segmented_music.py** (10 connections) — `tests/tools/test_audio_mixer_segmented_music.py`
- **test_audio_mixer_track_fades.py** (10 connections) — `tests/tools/test_audio_mixer_track_fades.py`
- **.execute()** (8 connections) — `tools/capture/cap_recorder.py`
- **_find_cap_recordings_dir()** (8 connections) — `tools/capture/cap_recorder.py`
- **test_remotion_audio_mux.py** (8 connections) — `tests/tools/test_remotion_audio_mux.py`
- **_find_cap_binary()** (7 connections) — `tools/capture/cap_recorder.py`
- **platform** (7 connections)
- **._detect()** (6 connections) — `tools/capture/cap_recorder.py`
- **._status()** (6 connections) — `tools/capture/cap_recorder.py`
- **_get_recent_recordings()** (6 connections) — `tools/capture/cap_recorder.py`
- **_is_cap_running()** (6 connections) — `tools/capture/cap_recorder.py`
- **._build_command()** (6 connections) — `tools/capture/screen_recorder.py`
- **test_remotion_caption_burn.py** (6 connections) — `tests/tools/test_remotion_caption_burn.py`
- **test_external_audio_mux_adds_audible_stream_without_changing_video_length()** (5 connections) — `tests/tools/test_remotion_audio_mux.py`
- **._find_recordings()** (5 connections) — `tools/capture/cap_recorder.py`
- **._pick_latest()** (5 connections) — `tools/capture/cap_recorder.py`
- **.execute()** (5 connections) — `tools/capture/screen_recorder.py`
- **._setup_guide()** (4 connections) — `tools/capture/cap_recorder.py`
- *... and 34 more nodes in this community*

## Relationships

- [Core Utilities](Core_Utilities.md) (57 shared connections)
- [Tool Testing](Tool_Testing.md) (30 shared connections)
- [Character Animation](Character_Animation.md) (16 shared connections)
- [Audio Mixer Tests](Audio_Mixer_Tests.md) (12 shared connections)
- [Environment Variable Loader](Environment_Variable_Loader.md) (6 shared connections)
- [Lyria BGM Generation](Lyria_BGM_Generation.md) (5 shared connections)
- [Hexagon Cube Visualization](Hexagon_Cube_Visualization.md) (5 shared connections)
- [Tool Execution](Tool_Execution.md) (4 shared connections)
- [Project Init](Project_Init.md) (4 shared connections)
- [Visual Evaluation System](Visual_Evaluation_System.md) (4 shared connections)
- [Event Stream](Event_Stream.md) (3 shared connections)
- [Remotion Demo Renderer](Remotion_Demo_Renderer.md) (3 shared connections)

## Source Files

- `scripts/backlot_screenshot_stage.py`
- `tests/qa/test_04_audio_mix.py`
- `tests/qa/test_06_video_stitch.py`
- `tests/tools/test_audio_mixer_segmented_music.py`
- `tests/tools/test_audio_mixer_track_fades.py`
- `tests/tools/test_remotion_audio_mux.py`
- `tests/tools/test_remotion_caption_burn.py`
- `tools/audio/audio_mixer.py`
- `tools/capture/cap_recorder.py`
- `tools/capture/screen_recorder.py`

## Audit Trail

- EXTRACTED: 278 (95%)
- INFERRED: 15 (5%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*