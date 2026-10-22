# 3D Asset Tests

> 34 nodes · cohesion 0.10

## Key Concepts

- **test_3d_asset_generation.py** (27 connections) — `tests/tools/test_3d_asset_generation.py`
- **blender_world.py** (22 connections) — `tools/graphics/blender_world.py`
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
- *... and 9 more nodes in this community*

## Relationships

- [Core Utilities](Core_Utilities.md) (29 shared connections)
- [Tool Testing](Tool_Testing.md) (22 shared connections)
- [Tool Execution](Tool_Execution.md) (10 shared connections)
- [Character Animation](Character_Animation.md) (7 shared connections)
- [Response Handler Tests](Response_Handler_Tests.md) (5 shared connections)
- [Tool Registry](Tool_Registry.md) (2 shared connections)
- [Audio Mixing](Audio_Mixing.md) (2 shared connections)
- [Playbook Generator](Playbook_Generator.md) (1 shared connections)
- [MiniMax Image](MiniMax_Image.md) (1 shared connections)

## Source Files

- `tests/tools/test_3d_asset_generation.py`
- `tools/graphics/atlas_3d.py`
- `tools/graphics/blender_world.py`
- `tools/graphics/fal_3d.py`

## Audit Trail

- EXTRACTED: 105 (77%)
- INFERRED: 32 (23%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*