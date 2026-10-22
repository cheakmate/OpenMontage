# Media Profile Manager

> 18 nodes · cohesion 0.16

## Key Concepts

- **get_profile()** (15 connections) — `lib/media_profiles.py`
- **media_profiles.py** (10 connections) — `lib/media_profiles.py`
- **ffmpeg_output_args()** (6 connections) — `lib/media_profiles.py`
- **MediaProfile** (5 connections) — `lib/media_profiles.py`
- **TestMediaProfiles** (5 connections) — `tests/contracts/test_phase0_contracts.py`
- **AspectRatio** (3 connections) — `lib/media_profiles.py`
- **get_profiles_for_platform()** (3 connections) — `lib/media_profiles.py`
- **.test_ffmpeg_args()** (3 connections) — `tests/contracts/test_phase0_contracts.py`
- **.test_get_profile()** (2 connections) — `tests/contracts/test_phase0_contracts.py`
- **.test_unknown_profile_raises()** (2 connections) — `tests/contracts/test_phase0_contracts.py`
- **Enum** (2 connections)
- **.test_all_profiles_exist()** (1 connections) — `tests/contracts/test_phase0_contracts.py`
- **str** (1 connections)
- **Internal media profile constants and render-profile helpers. Defines platform-…** (1 connections) — `lib/media_profiles.py`
- **Get a media profile by name.** (1 connections) — `lib/media_profiles.py`
- **Get all profiles matching a platform prefix.** (1 connections) — `lib/media_profiles.py`
- **Generate FFmpeg output arguments for a media profile.** (1 connections) — `lib/media_profiles.py`
- **A named render profile for a target platform/format.** (1 connections) — `lib/media_profiles.py`

## Relationships

- [Pipeline Loader](Pipeline_Loader.md) (4 shared connections)
- [Core Utilities](Core_Utilities.md) (4 shared connections)
- [Video Composition](Video_Composition.md) (3 shared connections)
- [HyperFrames Render](HyperFrames_Render.md) (1 shared connections)
- [Clip Preflight](Clip_Preflight.md) (1 shared connections)
- [Tool Testing](Tool_Testing.md) (1 shared connections)
- [Delivery Promise Classifier](Delivery_Promise_Classifier.md) (1 shared connections)

## Source Files

- `lib/media_profiles.py`
- `tests/contracts/test_phase0_contracts.py`

## Audit Trail

- EXTRACTED: 39 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*