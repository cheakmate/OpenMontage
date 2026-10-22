# Subtitle Generation Tests

> 67 nodes · cohesion 0.06

## Key Concepts

- **AzureSpeechToText** (36 connections) — `tools/analysis/azure_stt.py`
- **SubtitleGen** (33 connections) — `tools/subtitle/subtitle_gen.py`
- **.execute()** (12 connections) — `tools/subtitle/subtitle_gen.py`
- **test_subtitle_timestamps.py** (10 connections) — `tests/tools/test_subtitle_timestamps.py`
- **TestContract** (9 connections) — `tests/tools/test_azure_stt.py`
- **._transcribe()** (8 connections) — `tools/analysis/azure_stt.py`
- **._ts_srt()** (8 connections) — `tools/subtitle/subtitle_gen.py`
- **TestSubtitleGenUnit** (7 connections) — `tests/contracts/test_phase1_contracts.py`
- **TestParsePayload** (7 connections) — `tests/tools/test_azure_stt.py`
- **TestStatus** (7 connections) — `tests/tools/test_azure_stt.py`
- **._parse_payload()** (7 connections) — `tools/analysis/azure_stt.py`
- **._ts_vtt()** (7 connections) — `tools/subtitle/subtitle_gen.py`
- **TestExecute** (6 connections) — `tests/tools/test_azure_stt.py`
- **Any** (6 connections)
- **_FakeResponse** (5 connections) — `tests/tools/test_azure_stt.py`
- **.execute()** (5 connections) — `tools/analysis/azure_stt.py`
- **.test_segment_fallback_without_words()** (4 connections) — `tests/contracts/test_phase1_contracts.py`
- **.test_output_feeds_subtitle_gen()** (4 connections) — `tests/tools/test_azure_stt.py`
- **test_all_outputs_are_well_formed()** (4 connections) — `tests/tools/test_subtitle_timestamps.py`
- **test_millisecond_carry_does_not_overflow()** (4 connections) — `tests/tools/test_subtitle_timestamps.py`
- **test_normal_values_unchanged()** (4 connections) — `tests/tools/test_subtitle_timestamps.py`
- **.estimate_cost()** (4 connections) — `tools/analysis/azure_stt.py`
- **._hmsms()** (4 connections) — `tools/subtitle/subtitle_gen.py`
- **.test_subtitle_gen_always_available()** (3 connections) — `tests/contracts/test_phase1_contracts.py`
- **.test_json_generation()** (3 connections) — `tests/contracts/test_phase1_contracts.py`
- *... and 42 more nodes in this community*

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (34 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (5 shared connections)
- [Tool Status Reporting](Tool_Status_Reporting.md) (2 shared connections)
- [Atelier Project Scaffolding](Atelier_Project_Scaffolding.md) (1 shared connections)
- [Lyria BGM Generator](Lyria_BGM_Generator.md) (1 shared connections)

## Source Files

- `tests/contracts/test_phase1_contracts.py`
- `tests/tools/test_azure_stt.py`
- `tests/tools/test_subtitle_timestamps.py`
- `tools/analysis/azure_stt.py`
- `tools/subtitle/subtitle_gen.py`

## Audit Trail

- EXTRACTED: 127 (77%)
- INFERRED: 38 (23%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*