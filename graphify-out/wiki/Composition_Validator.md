# Composition Validator

> 9 nodes · cohesion 0.28

## Key Concepts

- **CompositionValidator** (16 connections) — `tools/analysis/composition_validator.py`
- **probe_duration()** (16 connections) — `tools/analysis/audio_probe.py`
- **.execute()** (5 connections) — `tools/analysis/composition_validator.py`
- **._result()** (3 connections) — `tools/analysis/composition_validator.py`
- **.estimate_cost()** (2 connections) — `tools/analysis/composition_validator.py`
- **.get_status()** (2 connections) — `tools/analysis/composition_validator.py`
- **Any** (2 connections)
- **Path** (1 connections)
- **Quick helper: return duration in seconds, or None on failure. Use this from…** (1 connections) — `tools/analysis/audio_probe.py`

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (17 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (3 shared connections)
- [HyperFrames Runtime Tests](HyperFrames_Runtime_Tests.md) (2 shared connections)
- [Kling Client Tests](Kling_Client_Tests.md) (2 shared connections)
- [Environment Loader](Environment_Loader.md) (1 shared connections)
- [DashScope TTS Tests](DashScope_TTS_Tests.md) (1 shared connections)
- [Doubao TTS Provider](Doubao_TTS_Provider.md) (1 shared connections)
- [TTS Provider Tests](TTS_Provider_Tests.md) (1 shared connections)

## Source Files

- `tools/analysis/audio_probe.py`
- `tools/analysis/composition_validator.py`

## Audit Trail

- EXTRACTED: 30 (79%)
- INFERRED: 8 (21%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*