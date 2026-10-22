# Scene Pacing Verification

> 22 nodes · cohesion 0.16

## Key Concepts

- **math** (36 connections)
- **test_audio_mixer_target_duration.py** (14 connections) — `tests/tools/test_audio_mixer_target_duration.py`
- **verify_scene_pacing.py** (8 connections) — `lib/verify_scene_pacing.py`
- **step_duration()** (6 connections) — `lib/verify_scene_pacing.py`
- **trace()** (6 connections) — `lib/verify_scene_pacing.py`
- **_tail_rms()** (6 connections) — `tests/tools/test_audio_mixer_target_duration.py`
- **test_full_mix_can_pin_the_composition_length()** (6 connections) — `tests/tools/test_audio_mixer_target_duration.py`
- **wave** (6 connections)
- **assert_alignment()** (5 connections) — `lib/verify_scene_pacing.py`
- **_tone()** (5 connections) — `tests/tools/test_audio_mixer_target_duration.py`
- **_duration()** (4 connections) — `tests/tools/test_audio_mixer_target_duration.py`
- **test_full_mix_rejects_invalid_target_duration()** (4 connections) — `tests/tools/test_audio_mixer_target_duration.py`
- **_aligned_video_duration()** (3 connections) — `scripts/kling_official_animated_explainer_e2e.py`
- **Any** (3 connections)
- **Path** (3 connections)
- **Landmark** (2 connections) — `lib/verify_scene_pacing.py`
- **struct** (2 connections)
- **parametrize** (1 connections)
- **Verify that a TerminalScene `steps` list paces with narration cues. Use from…** (1 connections) — `lib/verify_scene_pacing.py`
- **Return the cursor-advancement for a single step (frame-accurate). Pills DO NOT…** (1 connections) — `lib/verify_scene_pacing.py`
- **Walk the step list and print a video-time landmark for each visible event.…** (1 connections) — `lib/verify_scene_pacing.py`
- **Validate that every narration cue has a visual landmark within tolerance. Also…** (1 connections) — `lib/verify_scene_pacing.py`

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (9 shared connections)
- [Audio Mixer Tests](Audio_Mixer_Tests.md) (5 shared connections)
- [Kling Explainer E2E](Kling_Explainer_E2E.md) (3 shared connections)
- [Environment Loader](Environment_Loader.md) (3 shared connections)
- [Project Init Validation](Project_Init_Validation.md) (2 shared connections)
- [Block Collision Simulation](Block_Collision_Simulation.md) (2 shared connections)
- [3D Block Collision](3D_Block_Collision.md) (2 shared connections)
- [Collision Phase Space](Collision_Phase_Space.md) (2 shared connections)
- [Elastic Collision Animation](Elastic_Collision_Animation.md) (2 shared connections)
- [Lozenge Tiling Visualization](Lozenge_Tiling_Visualization.md) (2 shared connections)
- [Spring Mass Simulation](Spring_Mass_Simulation.md) (2 shared connections)
- [Sqrt Random Process Demo](Sqrt_Random_Process_Demo.md) (2 shared connections)

## Source Files

- `lib/verify_scene_pacing.py`
- `scripts/kling_official_animated_explainer_e2e.py`
- `tests/tools/test_audio_mixer_target_duration.py`

## Audit Trail

- EXTRACTED: 86 (99%)
- INFERRED: 1 (1%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*