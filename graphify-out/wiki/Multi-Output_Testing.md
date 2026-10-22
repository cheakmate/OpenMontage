# Multi-Output Testing

> 20 nodes · cohesion 0.13

## Key Concepts

- **TestDashscopeImageMultiOutput** (12 connections) — `tests/contracts/test_dashscope_tools.py`
- **._extract_image_urls()** (8 connections) — `tools/graphics/dashscope_image.py`
- **._resolve_output_paths()** (7 connections) — `tools/graphics/dashscope_image.py`
- **.test_execute_single_image_uses_base_path()** (6 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_extract_image_urls_skips_failed_choices()** (3 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_extract_image_urls_across_choices()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_extract_image_urls_empty_when_no_images()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_extract_image_urls_within_single_choice()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_resolve_output_paths_multiple_inserts_index()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_resolve_output_paths_multiple_without_extension()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_resolve_output_paths_single_unchanged()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **__init__()** (1 connections) — `tests/contracts/test_dashscope_tools.py`
- **json()** (1 connections) — `tests/contracts/test_dashscope_tools.py`
- **raise_for_status()** (1 connections) — `tests/contracts/test_dashscope_tools.py`
- **Path** (1 connections)
- **Regression tests for PR #240 review: the tool advertised multiple_outputs and…** (1 connections) — `tests/contracts/test_dashscope_tools.py`
- **Per Qwen Cloud docs, a multi-output task can be SUCCEEDED with partial…** (1 connections) — `tests/contracts/test_dashscope_tools.py`
- **n=1 must keep the legacy single-path behavior (no _1 suffix).** (1 connections) — `tests/contracts/test_dashscope_tools.py`
- **Collect image URLs from every choice whose finish_reason is "stop". Per Qwen…** (1 connections) — `tools/graphics/dashscope_image.py`
- **Derive distinct paths for `count` images. Single image keeps the base path…** (1 connections) — `tools/graphics/dashscope_image.py`

## Relationships

- [DashScope API Testing](DashScope_API_Testing.md) (7 shared connections)
- [Tool Testing](Tool_Testing.md) (1 shared connections)
- [Image Download Tests](Image_Download_Tests.md) (1 shared connections)

## Source Files

- `tests/contracts/test_dashscope_tools.py`
- `tools/graphics/dashscope_image.py`

## Audit Trail

- EXTRACTED: 32 (97%)
- INFERRED: 1 (3%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*