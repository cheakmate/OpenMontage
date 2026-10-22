# Audio Mixer Testing

> 25 nodes · cohesion 0.18

## Key Concepts

- **test_audio_mixer_amix_normalize.py** (25 connections) — `tests/tools/test_audio_mixer_amix_normalize.py`
- **_build()** (10 connections) — `tests/tools/test_audio_mixer_amix_normalize.py`
- **test_sequential_lines_keep_standalone_peak()** (8 connections) — `tests/tools/test_audio_mixer_amix_normalize.py`
- **test_overlapping_tracks_are_limited_not_clipped()** (7 connections) — `tests/tools/test_audio_mixer_amix_normalize.py`
- **_assert_all_amix_unnormalized()** (6 connections) — `tests/tools/test_audio_mixer_amix_normalize.py`
- **_stub_tracks()** (6 connections) — `tests/tools/test_audio_mixer_amix_normalize.py`
- **test_duck_keeps_speech_at_unity()** (6 connections) — `tests/tools/test_audio_mixer_amix_normalize.py`
- **_levels()** (5 connections) — `tests/tools/test_audio_mixer_amix_normalize.py`
- **_tone()** (5 connections) — `tests/tools/test_audio_mixer_amix_normalize.py`
- **_render()** (4 connections) — `tests/tools/test_audio_mixer_amix_normalize.py`
- **test_full_mix_with_ducking_every_amix_disables_normalize()** (4 connections) — `tests/tools/test_audio_mixer_amix_normalize.py`
- **test_full_mix_without_ducking_amix_disables_normalize()** (4 connections) — `tests/tools/test_audio_mixer_amix_normalize.py`
- **test_loudnorm_output_has_no_extra_limiter()** (4 connections) — `tests/tools/test_audio_mixer_amix_normalize.py`
- **test_mix_amix_disables_normalize()** (4 connections) — `tests/tools/test_audio_mixer_amix_normalize.py`
- **test_output_without_loudnorm_ends_in_limiter()** (4 connections) — `tests/tools/test_audio_mixer_amix_normalize.py`
- **parametrize** (4 connections)
- **test_duck_amix_disables_normalize()** (3 connections) — `tests/tools/test_audio_mixer_amix_normalize.py`
- **needs_ffmpeg** (3 connections)
- **_amix_nodes()** (2 connections) — `tests/tools/test_audio_mixer_amix_normalize.py`
- **fake_run()** (1 connections) — `tests/tools/test_audio_mixer_amix_normalize.py`
- **Regression tests: amix must not scale tracks by 1/N. ffmpeg's `amix` defaults…** (1 connections) — `tests/tools/test_audio_mixer_amix_normalize.py`
- **Return (max_volume, mean_volume) in dB, as reported by volumedetect.** (1 connections) — `tests/tools/test_audio_mixer_amix_normalize.py`
- **Six narration lines: each line's peak in the mix equals its own peak.** (1 connections) — `tests/tools/test_audio_mixer_amix_normalize.py`
- **Six in-phase -6 dBFS tones at t=0 sum to +9.5 dBFS without normalize.** (1 connections) — `tests/tools/test_audio_mixer_amix_normalize.py`
- **Run the tool with ffmpeg stubbed out; return (filter graph, -map label).** (1 connections) — `tests/tools/test_audio_mixer_amix_normalize.py`

## Relationships

- [Audio Mixer Tests](Audio_Mixer_Tests.md) (5 shared connections)
- [Core Utilities](Core_Utilities.md) (2 shared connections)
- [Audio Mixing](Audio_Mixing.md) (2 shared connections)
- [Wikimedia Media Adapter](Wikimedia_Media_Adapter.md) (1 shared connections)
- [Lyria BGM Generation](Lyria_BGM_Generation.md) (1 shared connections)
- [Project Init](Project_Init.md) (1 shared connections)

## Source Files

- `tests/tools/test_audio_mixer_amix_normalize.py`

## Audit Trail

- EXTRACTED: 62 (94%)
- INFERRED: 4 (6%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*