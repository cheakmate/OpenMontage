# Cinematic Remotion Adapter

> 93 nodes · cohesion 0.04

## Key Concepts

- **VideoCompose** (125 connections) — `tools/video/video_compose.py`
- **Any** (18 connections)
- **._remotion_render()** (17 connections) — `tools/video/video_compose.py`
- **._render()** (16 connections) — `tools/video/video_compose.py`
- **._compose()** (14 connections) — `tools/video/video_compose.py`
- **.execute()** (12 connections) — `tools/video/video_compose.py`
- **Path** (12 connections)
- **._render_via_hyperframes()** (11 connections) — `tools/video/video_compose.py`
- **._run_final_review()** (11 connections) — `tools/video/video_compose.py`
- **test_cinematic_remotion_adapter.py** (11 connections) — `tests/tools/test_cinematic_remotion_adapter.py`
- **._compare_transcript_to_script()** (10 connections) — `tools/video/video_compose.py`
- **._render_via_atelier()** (10 connections) — `tools/video/video_compose.py`
- **._render_via_ffmpeg()** (9 connections) — `tools/video/video_compose.py`
- **._stage_remotion_media()** (9 connections) — `tools/video/video_compose.py`
- **._burn_subtitles()** (7 connections) — `tools/video/video_compose.py`
- **._encode()** (7 connections) — `tools/video/video_compose.py`
- **.get_info()** (7 connections) — `tools/video/video_compose.py`
- **._mux_external_audio()** (7 connections) — `tools/video/video_compose.py`
- **._pre_compose_validation()** (7 connections) — `tools/video/video_compose.py`
- **._cuts_to_cinematic_scenes()** (6 connections) — `tools/video/video_compose.py`
- **._overlay()** (6 connections) — `tools/video/video_compose.py`
- **._read_text_file()** (6 connections) — `tools/video/video_compose.py`
- **._build_theme_from_playbook()** (5 connections) — `tools/video/video_compose.py`
- **._hyperframes_available()** (5 connections) — `tools/video/video_compose.py`
- **._run_atelier_checks()** (5 connections) — `tools/video/video_compose.py`
- *... and 68 more nodes in this community*

## Relationships

- [Character Animation Tests](Character_Animation_Tests.md) (17 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (15 shared connections)
- [HyperFrames Runtime Tests](HyperFrames_Runtime_Tests.md) (15 shared connections)
- [Remotion Media Staging Tests](Remotion_Media_Staging_Tests.md) (13 shared connections)
- [ManimGL ML Examples](ManimGL_ML_Examples.md) (8 shared connections)
- [Video Review Tooling](Video_Review_Tooling.md) (7 shared connections)
- [Documentary Governance Tests](Documentary_Governance_Tests.md) (6 shared connections)
- [Lyria BGM Generator](Lyria_BGM_Generator.md) (5 shared connections)
- [Vertical Video Tests](Vertical_Video_Tests.md) (4 shared connections)
- [Delivery Promise Classifier](Delivery_Promise_Classifier.md) (4 shared connections)
- [Remotion Timeout Tests](Remotion_Timeout_Tests.md) (4 shared connections)
- [Environment Loader](Environment_Loader.md) (3 shared connections)

## Source Files

- `tests/contracts/test_phase1_contracts.py`
- `tests/contracts/test_phase3_contracts.py`
- `tests/tools/test_cinematic_remotion_adapter.py`
- `tests/tools/test_documentary_governance.py`
- `tests/tools/test_hyperframes_compose.py`
- `tests/tools/test_remotion_diagnostics.py`
- `tests/tools/test_remotion_media_staging.py`
- `tests/tools/test_unicode_tokenizers.py`
- `tools/video/video_compose.py`

## Audit Trail

- EXTRACTED: 264 (84%)
- INFERRED: 49 (16%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*