# TTS Provider Selector

> 18 nodes · cohesion 0.23

## Key Concepts

- **TTSSelector** (32 connections) — `tools/audio/tts_selector.py`
- **.execute()** (12 connections) — `tools/audio/tts_selector.py`
- **._providers()** (8 connections) — `tools/audio/tts_selector.py`
- **._select_best_tool()** (8 connections) — `tools/audio/tts_selector.py`
- **Any** (7 connections)
- **._adapt_inputs()** (5 connections) — `tools/audio/tts_selector.py`
- **.estimate_cost()** (5 connections) — `tools/audio/tts_selector.py`
- **._prepare_task_context()** (5 connections) — `tools/audio/tts_selector.py`
- **._tool_context_payload()** (5 connections) — `tools/audio/tts_selector.py`
- **._serialize_rankings()** (4 connections) — `tools/audio/tts_selector.py`
- **.fallback_tools()** (3 connections) — `tools/audio/tts_selector.py`
- **.provider_matrix()** (3 connections) — `tools/audio/tts_selector.py`
- **.get_status()** (3 connections) — `tools/audio/tts_selector.py`
- **Auto-discover TTS providers from the registry.** (1 connections) — `tools/audio/tts_selector.py`
- **Dynamically built from discovered providers.** (1 connections) — `tools/audio/tts_selector.py`
- **Built at runtime from each provider's best_for field.** (1 connections) — `tools/audio/tts_selector.py`
- **Translate capability-level controls to provider-native inputs.** (1 connections) — `tools/audio/tts_selector.py`
- **Select the best TTS provider using scored ranking.** (1 connections) — `tools/audio/tts_selector.py`

## Relationships

- [Core Utilities](Core_Utilities.md) (9 shared connections)
- [Fal TTS Testing](Fal_TTS_Testing.md) (3 shared connections)
- [Fish Audio TTS](Fish_Audio_TTS.md) (3 shared connections)
- [Tool Execution](Tool_Execution.md) (3 shared connections)
- [Path Scoring](Path_Scoring.md) (3 shared connections)
- [Dashscope Registry Tests](Dashscope_Registry_Tests.md) (2 shared connections)
- [Tool Contract Tests](Tool_Contract_Tests.md) (2 shared connections)
- [Tool Testing](Tool_Testing.md) (2 shared connections)
- [Character Animation](Character_Animation.md) (2 shared connections)
- [Provider Refresh](Provider_Refresh.md) (2 shared connections)
- [Tool Registry](Tool_Registry.md) (1 shared connections)
- [Tool Contracts](Tool_Contracts.md) (1 shared connections)

## Source Files

- `tools/audio/tts_selector.py`

## Audit Trail

- EXTRACTED: 59 (84%)
- INFERRED: 11 (16%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*