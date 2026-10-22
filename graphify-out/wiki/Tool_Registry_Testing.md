# Tool Registry Testing

> 21 nodes · cohesion 0.12

## Key Concepts

- **_DummySource** (8 connections) — `tests/tools/test_documentary_governance.py`
- **_scrub_unicode_dashes()** (8 connections) — `tools/tool_registry.py`
- **.ensure_discovered()** (8 connections) — `tools/tool_registry.py`
- **.test_registry_catalog_views()** (7 connections) — `tests/contracts/test_phase3_contracts.py`
- **.provider_menu_summary()** (7 connections) — `tools/tool_registry.py`
- **test_provider_menu_preserves_tool_discovery_metadata()** (6 connections) — `tests/tools/test_documentary_governance.py`
- **.provider_menu()** (6 connections) — `tools/tool_registry.py`
- **Any** (6 connections)
- **.capability_catalog()** (5 connections) — `tools/tool_registry.py`
- **.provider_catalog()** (4 connections) — `tools/tool_registry.py`
- **.download()** (2 connections) — `tests/tools/test_documentary_governance.py`
- **.__init__()** (1 connections) — `tests/tools/test_documentary_governance.py`
- **.is_available()** (1 connections) — `tests/tools/test_documentary_governance.py`
- **.search()** (1 connections) — `tests/tools/test_documentary_governance.py`
- **Path** (1 connections)
- **Load tool modules once before reporting capabilities.** (1 connections) — `tools/tool_registry.py`
- **Group the support envelope by top-level capability.** (1 connections) — `tools/tool_registry.py`
- **Group the support envelope by provider.** (1 connections) — `tools/tool_registry.py`
- **Generate a capability-grouped provider menu for user-facing display. Returns a…** (1 connections) — `tools/tool_registry.py`
- **Compact, human-ready rollup of provider_menu() for onboarding/preflight.…** (1 connections) — `tools/tool_registry.py`
- **Recursively normalize unicode punctuation in str leaves to ASCII. Used to keep…** (1 connections) — `tools/tool_registry.py`

## Relationships

- [Tool Registry](Tool_Registry.md) (12 shared connections)
- [Tool Execution](Tool_Execution.md) (6 shared connections)
- [ElevenLabs TTS Testing](ElevenLabs_TTS_Testing.md) (2 shared connections)
- [Style Bridge](Style_Bridge.md) (2 shared connections)
- [TTS Provider Tests](TTS_Provider_Tests.md) (1 shared connections)
- [Tool Contracts](Tool_Contracts.md) (1 shared connections)
- [Atlas Tool Tests](Atlas_Tool_Tests.md) (1 shared connections)

## Source Files

- `tests/contracts/test_phase3_contracts.py`
- `tests/tools/test_documentary_governance.py`
- `tools/tool_registry.py`

## Audit Trail

- EXTRACTED: 46 (90%)
- INFERRED: 5 (10%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*