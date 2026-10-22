# Dashscope Registry Tests

> 5 nodes · cohesion 0.40

## Key Concepts

- **TestDashscopeRegistryDiscovery** (9 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_image_selector_finds_dashscope()** (4 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_tts_selector_finds_dashscope()** (4 connections) — `tests/contracts/test_dashscope_tools.py`
- **image_selector should auto-discover dashscope_image by capability.** (1 connections) — `tests/contracts/test_dashscope_tools.py`
- **tts_selector should auto-discover dashscope_tts by capability.** (1 connections) — `tests/contracts/test_dashscope_tools.py`

## Relationships

- [Tool Registry](Tool_Registry.md) (2 shared connections)
- [Image Selector](Image_Selector.md) (2 shared connections)
- [DashScope API Testing](DashScope_API_Testing.md) (2 shared connections)
- [TTS Provider Selector](TTS_Provider_Selector.md) (2 shared connections)
- [Piper TTS Fallback](Piper_TTS_Fallback.md) (2 shared connections)
- [Tool Testing](Tool_Testing.md) (1 shared connections)

## Source Files

- `tests/contracts/test_dashscope_tools.py`

## Audit Trail

- EXTRACTED: 10 (67%)
- INFERRED: 5 (33%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*