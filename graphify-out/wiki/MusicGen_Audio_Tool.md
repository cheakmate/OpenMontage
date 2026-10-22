# MusicGen Audio Tool

> 23 nodes · cohesion 0.14

## Key Concepts

- **MusicGen** (26 connections) — `tools/audio/music_gen.py`
- **test_music_gen_force_instrumental.py** (10 connections) — `tests/tools/test_music_gen_force_instrumental.py`
- **_install_fake_requests()** (8 connections) — `tests/tools/test_music_gen_force_instrumental.py`
- **TestMusicGen** (5 connections) — `tests/contracts/test_phase3_contracts.py`
- **.execute()** (5 connections) — `tools/audio/music_gen.py`
- **_FakeResponse** (4 connections) — `tests/tools/test_music_gen_force_instrumental.py`
- **.estimate_cost()** (4 connections) — `tools/audio/music_gen.py`
- **._generate()** (4 connections) — `tools/audio/music_gen.py`
- **.test_cost_estimate_scales_with_duration()** (3 connections) — `tests/contracts/test_phase3_contracts.py`
- **test_explicit_vocal_opt_out_is_respected()** (3 connections) — `tests/tools/test_music_gen_force_instrumental.py`
- **test_force_instrumental_is_sent_true_by_default()** (3 connections) — `tests/tools/test_music_gen_force_instrumental.py`
- **Any** (3 connections)
- **.test_capabilities()** (2 connections) — `tests/contracts/test_phase3_contracts.py`
- **.test_identity()** (2 connections) — `tests/contracts/test_phase3_contracts.py`
- **fake_post()** (2 connections) — `tests/tools/test_music_gen_force_instrumental.py`
- **test_schema_defaults_force_instrumental_to_true()** (2 connections) — `tests/tools/test_music_gen_force_instrumental.py`
- **.get_status()** (2 connections) — `tools/audio/music_gen.py`
- **.__init__()** (1 connections) — `tests/tools/test_music_gen_force_instrumental.py`
- **.raise_for_status()** (1 connections) — `tests/tools/test_music_gen_force_instrumental.py`
- **ModuleType** (1 connections)
- **MonkeyPatch** (1 connections)
- **Regression for the force_instrumental mandate (REVIEW §8 #8).…** (1 connections) — `tests/tools/test_music_gen_force_instrumental.py`
- **Install a stub ``requests`` module that records the JSON payload.** (1 connections) — `tests/tools/test_music_gen_force_instrumental.py`

## Relationships

- [Tool Testing](Tool_Testing.md) (6 shared connections)
- [Core Utilities](Core_Utilities.md) (4 shared connections)
- [Character Animation](Character_Animation.md) (3 shared connections)
- [Tool Contracts](Tool_Contracts.md) (2 shared connections)
- [Tool Registry](Tool_Registry.md) (2 shared connections)
- [Tool Execution](Tool_Execution.md) (2 shared connections)
- [Cinematic Scene Types](Cinematic_Scene_Types.md) (1 shared connections)
- [Lyria BGM Generation](Lyria_BGM_Generation.md) (1 shared connections)
- [Project Init](Project_Init.md) (1 shared connections)

## Source Files

- `tests/contracts/test_phase3_contracts.py`
- `tests/tools/test_music_gen_force_instrumental.py`
- `tools/audio/music_gen.py`

## Audit Trail

- EXTRACTED: 45 (78%)
- INFERRED: 13 (22%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*