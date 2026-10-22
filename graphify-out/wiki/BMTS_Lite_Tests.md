# BMTS Lite Tests

> 21 nodes · cohesion 0.20

## Key Concepts

- **DependencyError** (22 connections) — `tools/base_tool.py`
- **BgmMontageLite** (21 connections) — `tools/video/bmts_lite.py`
- **test_bmts_lite.py** (18 connections) — `tests/tools/test_bmts_lite.py`
- **.execute()** (11 connections) — `tools/video/bmts_lite.py`
- **.check_dependencies()** (10 connections) — `tools/base_tool.py`
- **test_run_emits_mp4_timeline_audiomap_and_openmontage_report()** (7 connections) — `tests/tools/test_bmts_lite.py`
- **.check_dependencies()** (6 connections) — `tools/video/bmts_lite.py`
- **test_existing_output_is_never_overwritten()** (5 connections) — `tests/tools/test_bmts_lite.py`
- **._engine_root()** (5 connections) — `tools/video/bmts_lite.py`
- **_inputs()** (4 connections) — `tests/tools/test_bmts_lite.py`
- **test_missing_video_fails_before_runtime_checks()** (4 connections) — `tests/tools/test_bmts_lite.py`
- **._python_executable()** (4 connections) — `tools/video/bmts_lite.py`
- **Path** (4 connections)
- **test_schema_and_registry_expose_a_reference_free_local_tool()** (3 connections) — `tests/tools/test_bmts_lite.py`
- **_fraction()** (3 connections) — `tools/video/bmts_lite.py`
- **Any** (2 connections)
- **fake_run()** (1 connections) — `tests/tools/test_bmts_lite.py`
- **Exception** (1 connections)
- **Path** (1 connections)
- **Verify all dependencies are installed. Raises DependencyError if not.** (1 connections) — `tools/base_tool.py`
- **Raised when a tool's dependency is not satisfied.** (1 connections) — `tools/base_tool.py`

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (20 shared connections)
- [Kling Client Tests](Kling_Client_Tests.md) (8 shared connections)
- [Tool Dependency Tests](Tool_Dependency_Tests.md) (3 shared connections)
- [Artifact Schema Validation](Artifact_Schema_Validation.md) (3 shared connections)
- [Pipeline Loader](Pipeline_Loader.md) (3 shared connections)
- [Kling Avatar LipSync Tests](Kling_Avatar_LipSync_Tests.md) (2 shared connections)
- [Kling LipSync Implementation](Kling_LipSync_Implementation.md) (2 shared connections)
- [Kling Video Tests](Kling_Video_Tests.md) (2 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (2 shared connections)
- [Kling Image Provider Tests](Kling_Image_Provider_Tests.md) (1 shared connections)
- [Image Selector Tests](Image_Selector_Tests.md) (1 shared connections)
- [Video Review Tooling](Video_Review_Tooling.md) (1 shared connections)

## Source Files

- `tests/tools/test_bmts_lite.py`
- `tools/base_tool.py`
- `tools/video/bmts_lite.py`

## Audit Trail

- EXTRACTED: 72 (78%)
- INFERRED: 20 (22%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*