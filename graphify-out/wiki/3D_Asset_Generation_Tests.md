# 3D Asset Generation Tests

> 32 nodes · cohesion 0.11

## Key Concepts

- **test_3d_asset_generation.py** (27 connections) — `tests/tools/test_3d_asset_generation.py`
- **Atlas3D** (17 connections) — `tools/graphics/atlas_3d.py`
- **Fal3D** (17 connections) — `tools/graphics/fal_3d.py`
- **BlenderWorld** (16 connections) — `tools/graphics/blender_world.py`
- **.execute()** (8 connections) — `tools/graphics/fal_3d.py`
- **.execute()** (7 connections) — `tools/graphics/atlas_3d.py`
- **test_atlas_cost_matrix_and_missing_key()** (6 connections) — `tests/tools/test_3d_asset_generation.py`
- **.execute()** (6 connections) — `tools/graphics/blender_world.py`
- **first_missing_frame()** (6 connections) — `tools/graphics/blender_world.py`
- **find_blender()** (5 connections) — `tools/graphics/blender_world.py`
- **_download_file()** (5 connections) — `tools/graphics/fal_3d.py`
- **test_fal_cost_matrix_and_input_validation()** (4 connections) — `tests/tools/test_3d_asset_generation.py`
- **.estimate_cost()** (4 connections) — `tools/graphics/atlas_3d.py`
- **.get_status()** (4 connections) — `tools/graphics/atlas_3d.py`
- **.estimate_cost()** (4 connections) — `tools/graphics/fal_3d.py`
- **_api_key()** (3 connections) — `tools/graphics/atlas_3d.py`
- **.estimate_runtime()** (3 connections) — `tools/graphics/blender_world.py`
- **.get_status()** (3 connections) — `tools/graphics/blender_world.py`
- **_api_key()** (3 connections) — `tools/graphics/fal_3d.py`
- **.get_status()** (3 connections) — `tools/graphics/fal_3d.py`
- **Any** (3 connections)
- **test_blender_doctor_explains_missing_optional_runtime()** (2 connections) — `tests/tools/test_3d_asset_generation.py`
- **test_blender_doctor_reports_detected_runtime()** (2 connections) — `tests/tools/test_3d_asset_generation.py`
- **test_blender_resume_finds_first_missing_contiguous_frame()** (2 connections) — `tests/tools/test_3d_asset_generation.py`
- **_extension()** (2 connections) — `tools/graphics/atlas_3d.py`
- *... and 7 more nodes in this community*

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (48 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (6 shared connections)
- [GLB Download Tests](GLB_Download_Tests.md) (5 shared connections)
- [TTS Provider Tests](TTS_Provider_Tests.md) (1 shared connections)
- [CogVideo Variant Tests](CogVideo_Variant_Tests.md) (1 shared connections)
- [Tool Registry Discovery Tests](Tool_Registry_Discovery_Tests.md) (1 shared connections)
- [Environment Loader](Environment_Loader.md) (1 shared connections)
- [Playbook Generation](Playbook_Generation.md) (1 shared connections)
- [MiniMax Image Tests](MiniMax_Image_Tests.md) (1 shared connections)
- [Tool Registry Discovery](Tool_Registry_Discovery.md) (1 shared connections)

## Source Files

- `tests/tools/test_3d_asset_generation.py`
- `tools/graphics/atlas_3d.py`
- `tools/graphics/blender_world.py`
- `tools/graphics/fal_3d.py`

## Audit Trail

- EXTRACTED: 87 (73%)
- INFERRED: 32 (27%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*