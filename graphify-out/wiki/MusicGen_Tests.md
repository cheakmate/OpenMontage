# MusicGen Tests

> 10 nodes · cohesion 0.38

## Key Concepts

- **MusicGen** (26 connections) — `tools/audio/music_gen.py`
- **TestMusicGen** (5 connections) — `tests/contracts/test_phase3_contracts.py`
- **.execute()** (5 connections) — `tools/audio/music_gen.py`
- **.estimate_cost()** (4 connections) — `tools/audio/music_gen.py`
- **._generate()** (4 connections) — `tools/audio/music_gen.py`
- **.test_cost_estimate_scales_with_duration()** (3 connections) — `tests/contracts/test_phase3_contracts.py`
- **Any** (3 connections)
- **.test_capabilities()** (2 connections) — `tests/contracts/test_phase3_contracts.py`
- **.test_identity()** (2 connections) — `tests/contracts/test_phase3_contracts.py`
- **.get_status()** (2 connections) — `tools/audio/music_gen.py`

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (13 shared connections)
- [Music Instrumental Tests](Music_Instrumental_Tests.md) (4 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (3 shared connections)
- [Piper TTS Tests](Piper_TTS_Tests.md) (2 shared connections)

## Source Files

- `tests/contracts/test_phase3_contracts.py`
- `tools/audio/music_gen.py`

## Audit Trail

- EXTRACTED: 27 (69%)
- INFERRED: 12 (31%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*