# Tool Registry Tests

> 11 nodes · cohesion 0.20

## Key Concepts

- **DummyTool** (9 connections) — `tests/contracts/test_phase0_contracts.py`
- **.test_register_and_find()** (8 connections) — `tests/contracts/test_phase0_contracts.py`
- **TestBaseTool** (7 connections) — `tests/contracts/test_phase0_contracts.py`
- **TestToolRegistry** (6 connections) — `tests/contracts/test_phase0_contracts.py`
- **.list_all()** (5 connections) — `tools/tool_registry.py`
- **.execute()** (2 connections) — `tests/contracts/test_phase0_contracts.py`
- **.test_execute()** (2 connections) — `tests/contracts/test_phase0_contracts.py`
- **.test_get_info()** (2 connections) — `tests/contracts/test_phase0_contracts.py`
- **.test_unavailable_when_deps_missing()** (2 connections) — `tests/contracts/test_phase0_contracts.py`
- **execute()** (2 connections) — `tests/contracts/test_phase0_contracts.py`
- **List all registered tool names.** (1 connections) — `tools/tool_registry.py`

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (5 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (4 shared connections)
- [Tool Registry Discovery](Tool_Registry_Discovery.md) (4 shared connections)
- [ComfyUI Setup Registry](ComfyUI_Setup_Registry.md) (3 shared connections)
- [Artifact Schema Validation](Artifact_Schema_Validation.md) (3 shared connections)
- [Tool Registry Discovery Tests](Tool_Registry_Discovery_Tests.md) (3 shared connections)
- [Piper TTS Tests](Piper_TTS_Tests.md) (2 shared connections)

## Source Files

- `tests/contracts/test_phase0_contracts.py`
- `tools/tool_registry.py`

## Audit Trail

- EXTRACTED: 21 (60%)
- INFERRED: 14 (40%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*