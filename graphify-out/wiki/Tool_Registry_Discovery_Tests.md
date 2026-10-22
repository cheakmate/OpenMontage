# Tool Registry Discovery Tests

> 35 nodes · cohesion 0.07

## Key Concepts

- **ToolRegistry** (101 connections) — `tools/tool_registry.py`
- **TestDashscopeRegistryDiscovery** (9 connections) — `tests/contracts/test_dashscope_tools.py`
- **.get_by_status()** (6 connections) — `tools/tool_registry.py`
- **.register_module()** (6 connections) — `tools/tool_registry.py`
- **TestPhase1ToolDiscovery** (5 connections) — `tests/contracts/test_phase1_contracts.py`
- **contracts/conftest.py** (5 connections) — `tests/contracts/conftest.py`
- **TestRegistryDiscovery** (4 connections) — `tests/contracts/test_jimeng_video.py`
- **isolated_tool_registry()** (4 connections) — `tests/contracts/conftest.py`
- **test_registry_registers_minimax_image_tool()** (4 connections) — `tests/tools/test_minimax_image.py`
- **.find_fallback()** (4 connections) — `tools/tool_registry.py`
- **.get_available()** (4 connections) — `tools/tool_registry.py`
- **.get_unavailable()** (4 connections) — `tools/tool_registry.py`
- **.test_all_three_tools_discoverable()** (3 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_discoverable()** (3 connections) — `tests/contracts/test_jimeng_video.py`
- **.test_distinct_from_other_minimax_tools()** (3 connections) — `tests/contracts/test_jimeng_video.py`
- **._load_dotenv()** (3 connections) — `tools/tool_registry.py`
- **.test_phase1_tools_are_core_tier()** (2 connections) — `tests/contracts/test_phase1_contracts.py`
- **.clear()** (2 connections) — `tools/tool_registry.py`
- **.gpu_required_tools()** (2 connections) — `tools/tool_registry.py`
- **.network_required_tools()** (2 connections) — `tools/tool_registry.py`
- **Get all tools that are currently available.** (2 connections) — `tools/tool_registry.py`
- **.__init__()** (1 connections) — `tools/tool_registry.py`
- **fixture** (1 connections)
- **ModuleType** (1 connections)
- **Shared fixtures for contract tests.** (1 connections) — `tests/contracts/conftest.py`
- *... and 10 more nodes in this community*

## Relationships

- [Tool Registry Discovery](Tool_Registry_Discovery.md) (33 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (22 shared connections)
- [ComfyUI Setup Registry](ComfyUI_Setup_Registry.md) (14 shared connections)
- [Piper TTS Tests](Piper_TTS_Tests.md) (5 shared connections)
- [Tool Registry Tests](Tool_Registry_Tests.md) (3 shared connections)
- [TTS Provider Tests](TTS_Provider_Tests.md) (3 shared connections)
- [DashScope Image Payload](DashScope_Image_Payload.md) (2 shared connections)
- [DashScope TTS Tests](DashScope_TTS_Tests.md) (2 shared connections)
- [Video Model Provider Tests](Video_Model_Provider_Tests.md) (2 shared connections)
- [MiniMax Image Tests](MiniMax_Image_Tests.md) (2 shared connections)
- [Image Selector Tests](Image_Selector_Tests.md) (1 shared connections)
- [TTS Provider Selector](TTS_Provider_Selector.md) (1 shared connections)

## Source Files

- `tests/contracts/conftest.py`
- `tests/contracts/test_dashscope_tools.py`
- `tests/contracts/test_jimeng_video.py`
- `tests/contracts/test_phase1_contracts.py`
- `tests/tools/test_minimax_image.py`
- `tools/tool_registry.py`

## Audit Trail

- EXTRACTED: 123 (82%)
- INFERRED: 27 (18%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*