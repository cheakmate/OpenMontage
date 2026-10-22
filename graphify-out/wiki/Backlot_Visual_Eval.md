# Backlot Visual Eval

> 24 nodes · cohesion 0.16

## Key Concepts

- **backlot_visual_eval.py** (22 connections) — `scripts/backlot_visual_eval.py`
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

- [Tool Base Runtime](Tool_Base_Runtime.md) (13 shared connections)
- [Environment Loader](Environment_Loader.md) (4 shared connections)
- [Lyria BGM Generator](Lyria_BGM_Generator.md) (4 shared connections)
- [Backlot Screenshot Capture](Backlot_Screenshot_Capture.md) (2 shared connections)
- [Event Logging](Event_Logging.md) (1 shared connections)
- [Tool Dependency Tests](Tool_Dependency_Tests.md) (1 shared connections)
- [Backlot Storyboard Server](Backlot_Storyboard_Server.md) (1 shared connections)

## Source Files

- `scripts/backlot_visual_eval.py`
- `tests/backlot/test_visual_eval.py`
- `tests/tools/test_bg_remove_api.py`

## Audit Trail

- EXTRACTED: 69 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*