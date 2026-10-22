# Preset Profile Tests

> 14 nodes · cohesion 0.14

## Key Concepts

- **TestPresets** (11 connections) — `tests/contracts/test_phase2_contracts.py`
- **.list_presets()** (3 connections) — `tools/audio/audio_enhance.py`
- **.list_profiles()** (3 connections) — `tools/enhancement/color_grade.py`
- **.list_presets()** (3 connections) — `tools/enhancement/face_enhance.py`
- **.test_audio_list_presets()** (2 connections) — `tests/contracts/test_phase2_contracts.py`
- **.test_color_list_profiles()** (2 connections) — `tests/contracts/test_phase2_contracts.py`
- **.test_face_list_presets()** (2 connections) — `tests/contracts/test_phase2_contracts.py`
- **.test_audio_presets_have_af()** (1 connections) — `tests/contracts/test_phase2_contracts.py`
- **.test_code_themes_have_required_fields()** (1 connections) — `tests/contracts/test_phase2_contracts.py`
- **.test_color_profiles_have_vf()** (1 connections) — `tests/contracts/test_phase2_contracts.py`
- **.test_face_presets_have_vf()** (1 connections) — `tests/contracts/test_phase2_contracts.py`
- **Return available presets and their descriptions.** (1 connections) — `tools/audio/audio_enhance.py`
- **Return available profiles and their descriptions.** (1 connections) — `tools/enhancement/color_grade.py`
- **Return available presets and their descriptions.** (1 connections) — `tools/enhancement/face_enhance.py`

## Relationships

- [Enhancement Error Tests](Enhancement_Error_Tests.md) (6 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (1 shared connections)

## Source Files

- `tests/contracts/test_phase2_contracts.py`
- `tools/audio/audio_enhance.py`
- `tools/enhancement/color_grade.py`
- `tools/enhancement/face_enhance.py`

## Audit Trail

- EXTRACTED: 17 (85%)
- INFERRED: 3 (15%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*