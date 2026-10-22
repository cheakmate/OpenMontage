# Environment Loader

> 62 nodes · cohesion 0.05

## Key Concepts

- **subprocess** (101 connections)
- **test_05_video_compose.py** (14 connections) — `tests/qa/test_05_video_compose.py`
- **test_sora_video.py** (14 connections) — `tests/tools/test_sora_video.py`
- **env_loader.py** (13 connections) — `lib/env_loader.py`
- **render_demo.py** (13 connections) — `render_demo.py`
- **test_audio_mixer_ducking.py** (12 connections) — `tests/tools/test_audio_mixer_ducking.py`
- **test_04_audio_mix.py** (11 connections) — `tests/qa/test_04_audio_mix.py`
- **test_06_video_stitch.py** (11 connections) — `tests/qa/test_06_video_stitch.py`
- **test_green_screen_chromakey.py** (10 connections) — `tests/tools/test_green_screen_chromakey.py`
- **load_env()** (8 connections) — `lib/env_loader.py`
- **test_remotion_audio_mux.py** (8 connections) — `tests/tools/test_remotion_audio_mux.py`
- **test_chromakey_preserves_frame_size_and_keys()** (7 connections) — `tests/tools/test_green_screen_chromakey.py`
- **main()** (5 connections) — `render_demo.py`
- **render_demo()** (5 connections) — `render_demo.py`
- **_has_audio()** (5 connections) — `tests/tools/test_audio_mixer_ducking.py`
- **_sine()** (5 connections) — `tests/tools/test_audio_mixer_ducking.py`
- **test_external_audio_mux_adds_audible_stream_without_changing_video_length()** (5 connections) — `tests/tools/test_remotion_audio_mux.py`
- **ensure_demo_environment()** (4 connections) — `render_demo.py`
- **validate_props_file()** (4 connections) — `render_demo.py`
- **test_full_mix_multi_narration_plus_music_with_ducking()** (4 connections) — `tests/tools/test_audio_mixer_ducking.py`
- **test_full_mix_single_narration_plus_music_with_ducking()** (4 connections) — `tests/tools/test_audio_mixer_ducking.py`
- **test_sora_video_reports_unavailable_when_openai_sdk_lacks_video_api()** (4 connections) — `tests/tools/test_sora_video.py`
- **discover_demos()** (3 connections) — `render_demo.py`
- **find_command()** (3 connections) — `render_demo.py`
- **generate_fixture()** (3 connections) — `tests/qa/test_04_audio_mix.py`
- *... and 37 more nodes in this community*

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (51 shared connections)
- [Lyria BGM Generator](Lyria_BGM_Generator.md) (14 shared connections)
- [Backlot Screenshot Capture](Backlot_Screenshot_Capture.md) (7 shared connections)
- [Audio Mixer Tests](Audio_Mixer_Tests.md) (6 shared connections)
- [Project Init Validation](Project_Init_Validation.md) (6 shared connections)
- [Kling Explainer E2E](Kling_Explainer_E2E.md) (4 shared connections)
- [Audio FFT Extraction](Audio_FFT_Extraction.md) (4 shared connections)
- [Backlot Visual Eval](Backlot_Visual_Eval.md) (4 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (4 shared connections)
- [Artifact Schema Validation](Artifact_Schema_Validation.md) (3 shared connections)
- [Chromakey Green Screen](Chromakey_Green_Screen.md) (3 shared connections)
- [Cinematic Remotion Adapter](Cinematic_Remotion_Adapter.md) (3 shared connections)

## Source Files

- `lib/env_loader.py`
- `render_demo.py`
- `tests/contracts/test_env_example.py`
- `tests/qa/test_04_audio_mix.py`
- `tests/qa/test_05_video_compose.py`
- `tests/qa/test_06_video_stitch.py`
- `tests/tools/test_audio_mixer_ducking.py`
- `tests/tools/test_green_screen_chromakey.py`
- `tests/tools/test_remotion_audio_mux.py`
- `tests/tools/test_sora_video.py`

## Audit Trail

- EXTRACTED: 241 (99%)
- INFERRED: 2 (1%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*