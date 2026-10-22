# Piper TTS Tests

> 20 nodes · cohesion 0.16

## Key Concepts

- **PiperTTS** (27 connections) — `tools/audio/piper_tts.py`
- **TestNewToolsRegistry** (9 connections) — `tests/contracts/test_phase3_contracts.py`
- **TestPiperTTS** (7 connections) — `tests/contracts/test_phase3_contracts.py`
- **.test_all_register()** (7 connections) — `tests/contracts/test_phase3_contracts.py`
- **.test_voice_tier_tools()** (7 connections) — `tests/contracts/test_phase3_contracts.py`
- **.get_by_tier()** (7 connections) — `tools/tool_registry.py`
- **.execute()** (5 connections) — `tools/audio/piper_tts.py`
- **.test_status_requires_piper_executable_even_if_python_package_imports()** (4 connections) — `tests/contracts/test_phase3_contracts.py`
- **._generate()** (4 connections) — `tools/audio/piper_tts.py`
- **.test_cost_is_free()** (3 connections) — `tests/contracts/test_phase3_contracts.py`
- **.estimate_cost()** (3 connections) — `tools/audio/piper_tts.py`
- **.get_status()** (3 connections) — `tools/audio/piper_tts.py`
- **.tier_summary()** (3 connections) — `tools/tool_registry.py`
- **Any** (3 connections)
- **.test_capabilities()** (2 connections) — `tests/contracts/test_phase3_contracts.py`
- **.test_identity()** (2 connections) — `tests/contracts/test_phase3_contracts.py`
- **fake_import()** (1 connections) — `tests/contracts/test_phase3_contracts.py`
- **F-12 regression: Piper generation shells out to `piper`, so importing the…** (1 connections) — `tests/contracts/test_phase3_contracts.py`
- **Get all tools in a given tier.** (1 connections) — `tools/tool_registry.py`
- **Summarize tool counts by tier and status. Returns: {"core": {"available": 5,…** (1 connections) — `tools/tool_registry.py`

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (18 shared connections)
- [Tool Registry Discovery Tests](Tool_Registry_Discovery_Tests.md) (5 shared connections)
- [TTS Provider Tests](TTS_Provider_Tests.md) (4 shared connections)
- [ElevenLabs TTS Timestamps](ElevenLabs_TTS_Timestamps.md) (3 shared connections)
- [ComfyUI Setup Registry](ComfyUI_Setup_Registry.md) (3 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (3 shared connections)
- [MusicGen Tests](MusicGen_Tests.md) (2 shared connections)
- [Tool Registry Tests](Tool_Registry_Tests.md) (2 shared connections)

## Source Files

- `tests/contracts/test_phase3_contracts.py`
- `tools/audio/piper_tts.py`
- `tools/tool_registry.py`

## Audit Trail

- EXTRACTED: 45 (64%)
- INFERRED: 25 (36%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*