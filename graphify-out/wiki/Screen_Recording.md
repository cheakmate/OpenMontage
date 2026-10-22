# Screen Recording

> 14 nodes · cohesion 0.20

## Key Concepts

- **ScreenRecorder** (15 connections) — `tools/capture/screen_recorder.py`
- **._build_command()** (6 connections) — `tools/capture/screen_recorder.py`
- **.execute()** (5 connections) — `tools/capture/screen_recorder.py`
- **_detect_audio_device_mac()** (4 connections) — `tools/capture/screen_recorder.py`
- **_detect_audio_device_windows()** (4 connections) — `tools/capture/screen_recorder.py`
- **._build_mac_cmd()** (3 connections) — `tools/capture/screen_recorder.py`
- **._build_windows_cmd()** (3 connections) — `tools/capture/screen_recorder.py`
- **._probe_resolution()** (3 connections) — `tools/capture/screen_recorder.py`
- **._build_linux_cmd()** (2 connections) — `tools/capture/screen_recorder.py`
- **Any** (1 connections)
- **Build platform-specific FFmpeg capture command.** (1 connections) — `tools/capture/screen_recorder.py`
- **Find a working audio input device on Windows via dshow.** (1 connections) — `tools/capture/screen_recorder.py`
- **Get video resolution via ffprobe.** (1 connections) — `tools/capture/screen_recorder.py`
- **Find the default audio input index on macOS via avfoundation.** (1 connections) — `tools/capture/screen_recorder.py`

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (10 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (2 shared connections)
- [Environment Loader](Environment_Loader.md) (2 shared connections)

## Source Files

- `tools/capture/screen_recorder.py`

## Audit Trail

- EXTRACTED: 25 (78%)
- INFERRED: 7 (22%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*