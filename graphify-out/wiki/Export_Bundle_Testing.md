# Export Bundle Testing

> 20 nodes · cohesion 0.19

## Key Concepts

- **test_export_bundle.py** (23 connections) — `tests/tools/test_export_bundle.py`
- **ExportBundle** (22 connections) — `tools/publishers/export_bundle.py`
- **_make_video()** (7 connections) — `tests/tools/test_export_bundle.py`
- **.execute()** (7 connections) — `tools/publishers/export_bundle.py`
- **test_contract_metadata()** (4 connections) — `tests/tools/test_export_bundle.py`
- **test_export_bundle_layout_and_publish_log()** (4 connections) — `tests/tools/test_export_bundle.py`
- **._chapter_lines()** (4 connections) — `tools/publishers/export_bundle.py`
- **._default_export_dir()** (4 connections) — `tools/publishers/export_bundle.py`
- **test_chapter_time_formatting_hours()** (3 connections) — `tests/tools/test_export_bundle.py`
- **test_default_export_dir_inside_project_workspace()** (3 connections) — `tests/tools/test_export_bundle.py`
- **test_infer_project_name()** (3 connections) — `tests/tools/test_export_bundle.py`
- **test_missing_optional_asset_errors()** (3 connections) — `tests/tools/test_export_bundle.py`
- **._infer_project_name()** (3 connections) — `tools/publishers/export_bundle.py`
- **test_missing_video_errors()** (2 connections) — `tests/tools/test_export_bundle.py`
- **._format_chapter_time()** (2 connections) — `tools/publishers/export_bundle.py`
- **Any** (2 connections)
- **Path** (2 connections)
- **Path** (1 connections)
- **Tests for the export_bundle publisher tool. Covers the tool contract, registry…** (1 connections) — `tests/tools/test_export_bundle.py`
- **Keep run output inside the project workspace. When the render lives at…** (1 connections) — `tools/publishers/export_bundle.py`

## Relationships

- [Core Utilities](Core_Utilities.md) (11 shared connections)
- [Media Review](Media_Review.md) (4 shared connections)
- [Tool Testing](Tool_Testing.md) (3 shared connections)
- [Tool Execution](Tool_Execution.md) (3 shared connections)
- [Character Animation](Character_Animation.md) (2 shared connections)
- [Project Init](Project_Init.md) (1 shared connections)
- [Tool Registry](Tool_Registry.md) (1 shared connections)
- [Lyria BGM Generation](Lyria_BGM_Generation.md) (1 shared connections)
- [Atlas Tool Tests](Atlas_Tool_Tests.md) (1 shared connections)

## Source Files

- `tests/tools/test_export_bundle.py`
- `tools/publishers/export_bundle.py`

## Audit Trail

- EXTRACTED: 55 (86%)
- INFERRED: 9 (14%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*