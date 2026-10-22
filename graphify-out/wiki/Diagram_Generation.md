# Diagram Generation

> 31 nodes · cohesion 0.12

## Key Concepts

- **DiagramGen** (23 connections) — `tools/graphics/diagram_gen.py`
- **CodeSnippet** (19 connections) — `tools/graphics/code_snippet.py`
- **.execute()** (8 connections) — `tools/graphics/diagram_gen.py`
- **TestCodeSnippetUnit** (7 connections) — `tests/contracts/test_phase2_contracts.py`
- **.execute()** (7 connections) — `tools/graphics/code_snippet.py`
- **._render_mermaid()** (7 connections) — `tools/graphics/diagram_gen.py`
- **TestDiagramGenUnit** (6 connections) — `tests/contracts/test_phase2_contracts.py`
- **.get_status()** (6 connections) — `tools/graphics/diagram_gen.py`
- **._render_boxes()** (6 connections) — `tools/graphics/diagram_gen.py`
- **._render_text_card()** (6 connections) — `tools/graphics/diagram_gen.py`
- **.has_deps()** (4 connections) — `tests/contracts/test_phase2_contracts.py`
- **.has_deps()** (4 connections) — `tests/contracts/test_phase2_contracts.py`
- **.test_render_mermaid_fallback()** (4 connections) — `tests/contracts/test_phase2_contracts.py`
- **.test_diagram_gen_empty_boxes()** (4 connections) — `tests/contracts/test_phase2_contracts.py`
- **._add_title_bar()** (4 connections) — `tools/graphics/code_snippet.py`
- **._has_pillow()** (4 connections) — `tools/graphics/diagram_gen.py`
- **Any** (4 connections)
- **.test_render_different_themes()** (3 connections) — `tests/contracts/test_phase2_contracts.py`
- **.test_render_python()** (3 connections) — `tests/contracts/test_phase2_contracts.py`
- **.test_render_with_title()** (3 connections) — `tests/contracts/test_phase2_contracts.py`
- **.test_render_box_diagram()** (3 connections) — `tests/contracts/test_phase2_contracts.py`
- **.get_status()** (3 connections) — `tools/graphics/code_snippet.py`
- **._has_mermaid()** (3 connections) — `tools/graphics/diagram_gen.py`
- **fixture** (2 connections)
- **.list_themes()** (1 connections) — `tools/graphics/code_snippet.py`
- *... and 6 more nodes in this community*

## Relationships

- [Core Utilities](Core_Utilities.md) (10 shared connections)
- [Character Animation](Character_Animation.md) (7 shared connections)
- [Phase Comparison](Phase_Comparison.md) (6 shared connections)
- [Tool Execution](Tool_Execution.md) (6 shared connections)
- [Tool Testing](Tool_Testing.md) (4 shared connections)
- [FFmpeg Tests](FFmpeg_Tests.md) (1 shared connections)

## Source Files

- `tests/contracts/test_phase2_contracts.py`
- `tools/graphics/code_snippet.py`
- `tools/graphics/diagram_gen.py`

## Audit Trail

- EXTRACTED: 64 (70%)
- INFERRED: 28 (30%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*