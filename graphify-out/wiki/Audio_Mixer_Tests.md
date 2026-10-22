# Audio Mixer Tests

> 41 nodes · cohesion 0.08

## Key Concepts

- **AudioMixer** (43 connections) — `tools/audio/audio_mixer.py`
- **test_audio_mixer_ducking.py** (12 connections) — `tests/tools/test_audio_mixer_ducking.py`
- **.execute()** (9 connections) — `tools/audio/audio_mixer.py`
- **._full_mix()** (9 connections) — `tools/audio/audio_mixer.py`
- **._mix()** (9 connections) — `tools/audio/audio_mixer.py`
- **Any** (8 connections)
- **._duck()** (7 connections) — `tools/audio/audio_mixer.py`
- **._extract()** (6 connections) — `tools/audio/audio_mixer.py`
- **._loudnorm_filter()** (6 connections) — `tools/audio/audio_mixer.py`
- **._segmented_music()** (6 connections) — `tools/audio/audio_mixer.py`
- **._track_filters()** (6 connections) — `tools/audio/audio_mixer.py`
- **_has_audio()** (5 connections) — `tests/tools/test_audio_mixer_ducking.py`
- **_sine()** (5 connections) — `tests/tools/test_audio_mixer_ducking.py`
- **test_segmented_music_preserves_narration_level()** (5 connections) — `tests/tools/test_audio_mixer_segmented_music.py`
- **test_delayed_track_fades_use_the_source_timeline()** (5 connections) — `tests/tools/test_audio_mixer_track_fades.py`
- **._limiter_filter()** (5 connections) — `tools/audio/audio_mixer.py`
- **test_full_mix_multi_narration_plus_music_with_ducking()** (4 connections) — `tests/tools/test_audio_mixer_ducking.py`
- **test_full_mix_single_narration_plus_music_with_ducking()** (4 connections) — `tests/tools/test_audio_mixer_ducking.py`
- **test_segmented_music_amix_disables_normalize()** (4 connections) — `tests/tools/test_audio_mixer_segmented_music.py`
- **test_delayed_track_with_fade_out_remains_audible_after_its_start()** (4 connections) — `tests/tools/test_audio_mixer_track_fades.py`
- **.test_audio_mixer_missing_tracks()** (3 connections) — `tests/contracts/test_phase1_contracts.py`
- **Path** (2 connections)
- **fake_run()** (1 connections) — `tests/tools/test_audio_mixer_segmented_music.py`
- **_mean_db()** (1 connections) — `tests/tools/test_audio_mixer_segmented_music.py`
- **fake_run()** (1 connections) — `tests/tools/test_audio_mixer_track_fades.py`
- *... and 16 more nodes in this community*

## Relationships

- [Audio Mixing](Audio_Mixing.md) (12 shared connections)
- [Hexagon Cube Visualization](Hexagon_Cube_Visualization.md) (7 shared connections)
- [Core Utilities](Core_Utilities.md) (7 shared connections)
- [Character Animation](Character_Animation.md) (7 shared connections)
- [FFmpeg Tests](FFmpeg_Tests.md) (6 shared connections)
- [Audio Mixer Testing](Audio_Mixer_Testing.md) (5 shared connections)
- [Video Trimmer Tests](Video_Trimmer_Tests.md) (2 shared connections)
- [Tool Testing](Tool_Testing.md) (2 shared connections)
- [Pipeline Checkpoints](Pipeline_Checkpoints.md) (1 shared connections)
- [Tool Status Checks](Tool_Status_Checks.md) (1 shared connections)
- [Lyria BGM Generation](Lyria_BGM_Generation.md) (1 shared connections)
- [Project Init](Project_Init.md) (1 shared connections)

## Source Files

- `tests/contracts/test_phase1_contracts.py`
- `tests/tools/test_audio_mixer_ducking.py`
- `tests/tools/test_audio_mixer_segmented_music.py`
- `tests/tools/test_audio_mixer_track_fades.py`
- `tools/audio/audio_mixer.py`

## Audit Trail

- EXTRACTED: 100 (84%)
- INFERRED: 19 (16%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*