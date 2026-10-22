# Enhancement Error Tests

> 18 nodes · cohesion 0.18

## Key Concepts

- **SceneDetect** (22 connections) — `tools/analysis/scene_detect.py`
- **ColorGrade** (17 connections) — `tools/enhancement/color_grade.py`
- **FaceEnhance** (17 connections) — `tools/enhancement/face_enhance.py`
- **AudioEnhance** (16 connections) — `tools/audio/audio_enhance.py`
- **TestPhase2ErrorHandling** (15 connections) — `tests/contracts/test_phase2_contracts.py`
- **.execute()** (7 connections) — `tools/enhancement/color_grade.py`
- **.execute()** (7 connections) — `tools/enhancement/face_enhance.py`
- **test_scene_detect_lavfi_escape.py** (6 connections) — `tests/tools/test_scene_detect_lavfi_escape.py`
- **.execute()** (5 connections) — `tools/audio/audio_enhance.py`
- **.test_audio_enhance_missing_file()** (3 connections) — `tests/contracts/test_phase2_contracts.py`
- **.test_color_grade_missing_file()** (3 connections) — `tests/contracts/test_phase2_contracts.py`
- **.test_face_enhance_missing_file()** (3 connections) — `tests/contracts/test_phase2_contracts.py`
- **.test_scene_detect_missing_file()** (3 connections) — `tests/contracts/test_phase2_contracts.py`
- **._build_filter()** (3 connections) — `tools/enhancement/color_grade.py`
- **._build_filter()** (3 connections) — `tools/enhancement/face_enhance.py`
- **Any** (2 connections)
- **Any** (2 connections)
- **Any** (1 connections)

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (37 shared connections)
- [Scene Detection](Scene_Detection.md) (9 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (8 shared connections)
- [Phase Comparison Tests](Phase_Comparison_Tests.md) (8 shared connections)
- [Preset Profile Tests](Preset_Profile_Tests.md) (6 shared connections)
- [Video Review Tooling](Video_Review_Tooling.md) (3 shared connections)
- [Image Selector Tests](Image_Selector_Tests.md) (2 shared connections)
- [Diagram Rendering Tests](Diagram_Rendering_Tests.md) (2 shared connections)
- [Tool Status Reporting](Tool_Status_Reporting.md) (2 shared connections)
- [Lyria BGM Generator](Lyria_BGM_Generator.md) (1 shared connections)
- [Tool Dependency Tests](Tool_Dependency_Tests.md) (1 shared connections)

## Source Files

- `tests/contracts/test_phase2_contracts.py`
- `tests/tools/test_scene_detect_lavfi_escape.py`
- `tools/analysis/scene_detect.py`
- `tools/audio/audio_enhance.py`
- `tools/enhancement/color_grade.py`
- `tools/enhancement/face_enhance.py`

## Audit Trail

- EXTRACTED: 61 (57%)
- INFERRED: 46 (43%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*