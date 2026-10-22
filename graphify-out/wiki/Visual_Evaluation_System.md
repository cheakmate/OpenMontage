# Visual Evaluation System

> 25 nodes · cohesion 0.15

## Key Concepts

- **backlot_visual_eval.py** (22 connections) — `scripts/backlot_visual_eval.py`
- **unittest_mock** (12 connections)
- **compare_images()** (8 connections) — `scripts/backlot_visual_eval.py`
- **main()** (8 connections) — `scripts/backlot_visual_eval.py`
- **test_visual_eval.py** (8 connections) — `tests/backlot/test_visual_eval.py`
- **compare_or_bless()** (6 connections) — `scripts/backlot_visual_eval.py`
- **pil** (6 connections)
- **capture_shots()** (5 connections) — `scripts/backlot_visual_eval.py`
- **run_interactions()** (5 connections) — `scripts/backlot_visual_eval.py`
- **start_server()** (5 connections) — `scripts/backlot_visual_eval.py`
- **Path** (5 connections)
- **test_bg_remove_api.py** (5 connections) — `tests/tools/test_bg_remove_api.py`
- **capture_screenshot()** (4 connections) — `scripts/backlot_visual_eval.py`
- **_img()** (4 connections) — `tests/backlot/test_visual_eval.py`
- **Any** (4 connections)
- **run_stage()** (3 connections) — `scripts/backlot_visual_eval.py`
- **test_compare_images_can_mask_regions()** (3 connections) — `tests/backlot/test_visual_eval.py`
- **test_compare_images_detects_large_drift()** (3 connections) — `tests/backlot/test_visual_eval.py`
- **test_bg_remove_selects_model_through_rembg_session()** (2 connections) — `tests/tools/test_bg_remove_api.py`
- **Popen** (1 connections)
- **Path** (1 connections)
- **Deterministic visual eval for Backlot. Stages the fictional Backlot projects,…** (1 connections) — `scripts/backlot_visual_eval.py`
- **Run browser interaction smoke through Python Playwright.** (1 connections) — `scripts/backlot_visual_eval.py`
- **Compare screenshots by changed-pixel ratio and write a red diff image.** (1 connections) — `scripts/backlot_visual_eval.py`
- **Tests for Backlot visual eval image comparison helpers.** (1 connections) — `tests/backlot/test_visual_eval.py`

## Relationships

- [Core Utilities](Core_Utilities.md) (8 shared connections)
- [Audio Mixing](Audio_Mixing.md) (4 shared connections)
- [Lyria BGM Generation](Lyria_BGM_Generation.md) (4 shared connections)
- [Tool Testing](Tool_Testing.md) (4 shared connections)
- [Tool Execution](Tool_Execution.md) (2 shared connections)
- [Event Stream](Event_Stream.md) (2 shared connections)
- [Backlot Project Management](Backlot_Project_Management.md) (1 shared connections)
- [Tool Contracts](Tool_Contracts.md) (1 shared connections)
- [Character Animation](Character_Animation.md) (1 shared connections)
- [BMTS Lite Tests](BMTS_Lite_Tests.md) (1 shared connections)
- [ElevenLabs TTS Testing](ElevenLabs_TTS_Testing.md) (1 shared connections)
- [ElevenLabs Audio Tests](ElevenLabs_Audio_Tests.md) (1 shared connections)

## Source Files

- `scripts/backlot_visual_eval.py`
- `tests/backlot/test_visual_eval.py`
- `tests/tools/test_bg_remove_api.py`

## Audit Trail

- EXTRACTED: 80 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*