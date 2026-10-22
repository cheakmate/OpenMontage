# Video Trimmer Tests

> 17 nodes · cohesion 0.23

## Key Concepts

- **VideoTrimmer** (23 connections) — `tools/video/video_trimmer.py`
- **TestPhase1ErrorHandling** (11 connections) — `tests/contracts/test_phase1_contracts.py`
- **.execute()** (10 connections) — `tools/video/video_trimmer.py`
- **test_video_trimmer_workspaces.py** (8 connections) — `tests/tools/test_video_trimmer_workspaces.py`
- **._speed()** (6 connections) — `tools/video/video_trimmer.py`
- **._concat()** (5 connections) — `tools/video/video_trimmer.py`
- **._cut()** (5 connections) — `tools/video/video_trimmer.py`
- **test_nested_concat_keeps_outer_file_list()** (4 connections) — `tests/tools/test_video_trimmer_workspaces.py`
- **test_partial_cut_is_removed_without_masking_error()** (4 connections) — `tests/tools/test_video_trimmer_workspaces.py`
- **Any** (4 connections)
- **.test_video_trimmer_missing_file()** (3 connections) — `tests/contracts/test_phase1_contracts.py`
- **test_existing_concat_directory_is_not_owned_by_call()** (3 connections) — `tests/tools/test_video_trimmer_workspaces.py`
- **._build_atempo_chain()** (3 connections) — `tools/video/video_trimmer.py`
- **run()** (1 connections) — `tests/tools/test_video_trimmer_workspaces.py`
- **fail()** (1 connections) — `tests/tools/test_video_trimmer_workspaces.py`
- **Concat calls must own their temporary files, including failed partial cuts.** (1 connections) — `tests/tools/test_video_trimmer_workspaces.py`
- **Build an atempo filter chain. atempo only accepts [0.5, 100.0].** (1 connections) — `tools/video/video_trimmer.py`

## Relationships

- [Core Utilities](Core_Utilities.md) (10 shared connections)
- [Character Animation](Character_Animation.md) (5 shared connections)
- [Tool Status Checks](Tool_Status_Checks.md) (4 shared connections)
- [Tool Testing](Tool_Testing.md) (3 shared connections)
- [FFmpeg Tests](FFmpeg_Tests.md) (3 shared connections)
- [Audio Mixer Tests](Audio_Mixer_Tests.md) (2 shared connections)
- [Video Composition](Video_Composition.md) (2 shared connections)
- [Frame Sampler Tests](Frame_Sampler_Tests.md) (1 shared connections)
- [Visual Evaluation System](Visual_Evaluation_System.md) (1 shared connections)

## Source Files

- `tests/contracts/test_phase1_contracts.py`
- `tests/tools/test_video_trimmer_workspaces.py`
- `tools/video/video_trimmer.py`

## Audit Trail

- EXTRACTED: 42 (68%)
- INFERRED: 20 (32%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*