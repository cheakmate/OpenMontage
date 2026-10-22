# Audio Mixer Tests

> 46 nodes · cohesion 0.07

## Key Concepts

- **AudioMixer** (43 connections) — `tools/audio/audio_mixer.py`
- **test_audio_mixer_loudnorm_target.py** (10 connections) — `tests/tools/test_audio_mixer_loudnorm_target.py`
- **test_audio_mixer_segmented_music.py** (10 connections) — `tests/tools/test_audio_mixer_segmented_music.py`
- **test_audio_mixer_track_fades.py** (10 connections) — `tests/tools/test_audio_mixer_track_fades.py`
- **.execute()** (9 connections) — `tools/audio/audio_mixer.py`
- **._full_mix()** (9 connections) — `tools/audio/audio_mixer.py`
- **._mix()** (9 connections) — `tools/audio/audio_mixer.py`
- **Any** (8 connections)
- **_filter()** (7 connections) — `tests/tools/test_audio_mixer_loudnorm_target.py`
- **._duck()** (7 connections) — `tools/audio/audio_mixer.py`
- **._extract()** (6 connections) — `tools/audio/audio_mixer.py`
- **._loudnorm_filter()** (6 connections) — `tools/audio/audio_mixer.py`
- **._segmented_music()** (6 connections) — `tools/audio/audio_mixer.py`
- **._track_filters()** (6 connections) — `tools/audio/audio_mixer.py`
- **test_segmented_music_preserves_narration_level()** (5 connections) — `tests/tools/test_audio_mixer_segmented_music.py`
- **test_delayed_track_fades_use_the_source_timeline()** (5 connections) — `tests/tools/test_audio_mixer_track_fades.py`
- **._limiter_filter()** (5 connections) — `tools/audio/audio_mixer.py`
- **test_segmented_music_amix_disables_normalize()** (4 connections) — `tests/tools/test_audio_mixer_segmented_music.py`
- **test_delayed_track_with_fade_out_remains_audible_after_its_start()** (4 connections) — `tests/tools/test_audio_mixer_track_fades.py`
- **.test_audio_mixer_missing_tracks()** (3 connections) — `tests/contracts/test_phase1_contracts.py`
- **test_schema_exposes_loudnorm_target_default()** (3 connections) — `tests/tools/test_audio_mixer_loudnorm_target.py`
- **test_default_target_is_podcast_minus_16()** (2 connections) — `tests/tools/test_audio_mixer_loudnorm_target.py`
- **test_non_numeric_target_falls_back_to_default()** (2 connections) — `tests/tools/test_audio_mixer_loudnorm_target.py`
- **test_out_of_range_target_is_clamped()** (2 connections) — `tests/tools/test_audio_mixer_loudnorm_target.py`
- **test_youtube_target_minus_14_is_honored()** (2 connections) — `tests/tools/test_audio_mixer_loudnorm_target.py`
- *... and 21 more nodes in this community*

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (15 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (7 shared connections)
- [Environment Loader](Environment_Loader.md) (6 shared connections)
- [Video Review Tooling](Video_Review_Tooling.md) (6 shared connections)
- [Audio Mix Normalization](Audio_Mix_Normalization.md) (5 shared connections)
- [Scene Pacing Verification](Scene_Pacing_Verification.md) (5 shared connections)
- [Frame Sampler Tests](Frame_Sampler_Tests.md) (2 shared connections)
- [Lyria BGM Generator](Lyria_BGM_Generator.md) (2 shared connections)
- [Project Init Validation](Project_Init_Validation.md) (2 shared connections)
- [Artifact Schema Validation](Artifact_Schema_Validation.md) (1 shared connections)
- [Tool Status Reporting](Tool_Status_Reporting.md) (1 shared connections)

## Source Files

- `tests/contracts/test_phase1_contracts.py`
- `tests/tools/test_audio_mixer_loudnorm_target.py`
- `tests/tools/test_audio_mixer_segmented_music.py`
- `tests/tools/test_audio_mixer_track_fades.py`
- `tools/audio/audio_mixer.py`

## Audit Trail

- EXTRACTED: 109 (85%)
- INFERRED: 19 (15%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*