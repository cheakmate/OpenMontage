# ComfyUI Setup Registry

> 25 nodes · cohesion 0.11

## Key Concepts

- **.register()** (13 connections) — `tools/tool_registry.py`
- **_scrub_unicode_dashes()** (8 connections) — `tools/tool_registry.py`
- **.ensure_discovered()** (8 connections) — `tools/tool_registry.py`
- **.test_registry_catalog_views()** (7 connections) — `tests/contracts/test_phase3_contracts.py`
- **.provider_menu_summary()** (7 connections) — `tools/tool_registry.py`
- **test_provider_menu_preserves_tool_discovery_metadata()** (6 connections) — `tests/tools/test_documentary_governance.py`
- **.provider_menu()** (6 connections) — `tools/tool_registry.py`
- **Any** (6 connections)
- **.test_registry_discovers_comfyui_music_under_music_generation()** (5 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_provider_menu_summary_includes_structured_setup_offer()** (5 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_support_envelope()** (5 connections) — `tests/contracts/test_phase0_contracts.py`
- **.capability_catalog()** (5 connections) — `tools/tool_registry.py`
- **.support_envelope()** (5 connections) — `tools/tool_registry.py`
- **TestComfyUISetupOffer** (4 connections) — `tests/contracts/test_comfyui_tools.py`
- **.provider_catalog()** (4 connections) — `tools/tool_registry.py`
- **test_provider_menu_summary_is_cp1252_safe()** (3 connections) — `tests/tools/test_hyperframes_compose.py`
- **Regression: on Windows cp1252 stdout, printing any string with an em-dash…** (1 connections) — `tests/tools/test_hyperframes_compose.py`
- **Load tool modules once before reporting capabilities.** (1 connections) — `tools/tool_registry.py`
- **Generate a full support-envelope report for all tools. Returns a dict mapping…** (1 connections) — `tools/tool_registry.py`
- **Group the support envelope by top-level capability.** (1 connections) — `tools/tool_registry.py`
- **Group the support envelope by provider.** (1 connections) — `tools/tool_registry.py`
- **Generate a capability-grouped provider menu for user-facing display. Returns a…** (1 connections) — `tools/tool_registry.py`
- **Compact, human-ready rollup of provider_menu() for onboarding/preflight.…** (1 connections) — `tools/tool_registry.py`
- **Recursively normalize unicode punctuation in str leaves to ASCII. Used to keep…** (1 connections) — `tools/tool_registry.py`
- **Register a tool instance.** (1 connections) — `tools/tool_registry.py`

## Relationships

- [Tool Registry Discovery Tests](Tool_Registry_Discovery_Tests.md) (14 shared connections)
- [Tool Registry Tests](Tool_Registry_Tests.md) (3 shared connections)
- [TTS Provider Tests](TTS_Provider_Tests.md) (3 shared connections)
- [Piper TTS Tests](Piper_TTS_Tests.md) (3 shared connections)
- [Documentary Governance Tests](Documentary_Governance_Tests.md) (3 shared connections)
- [Workflow Patching](Workflow_Patching.md) (2 shared connections)
- [ComfyUI Music Tests](ComfyUI_Music_Tests.md) (2 shared connections)
- [Tool Registry Discovery](Tool_Registry_Discovery.md) (2 shared connections)
- [HyperFrames Runtime Tests](HyperFrames_Runtime_Tests.md) (2 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (2 shared connections)
- [ComfyUI Tool Tests](ComfyUI_Tool_Tests.md) (1 shared connections)
- [ElevenLabs TTS Timestamps](ElevenLabs_TTS_Timestamps.md) (1 shared connections)

## Source Files

- `tests/contracts/test_comfyui_tools.py`
- `tests/contracts/test_phase0_contracts.py`
- `tests/contracts/test_phase3_contracts.py`
- `tests/tools/test_documentary_governance.py`
- `tests/tools/test_hyperframes_compose.py`
- `tools/tool_registry.py`

## Audit Trail

- EXTRACTED: 56 (78%)
- INFERRED: 16 (22%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*