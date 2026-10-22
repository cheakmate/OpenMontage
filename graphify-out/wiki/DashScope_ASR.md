# DashScope ASR

> 38 nodes · cohesion 0.11

## Key Concepts

- **DashscopeAsr** (38 connections) — `tools/analysis/dashscope_asr.py`
- **TestDashscopeAsrSpecific** (18 connections) — `tests/contracts/test_dashscope_tools.py`
- **.execute()** (10 connections) — `tools/analysis/dashscope_asr.py`
- **._transcribe()** (10 connections) — `tools/analysis/dashscope_asr.py`
- **Any** (8 connections)
- **._extract_words()** (6 connections) — `tools/analysis/dashscope_asr.py`
- **._build_payload()** (5 connections) — `tools/analysis/dashscope_asr.py`
- **._poll_task()** (5 connections) — `tools/analysis/dashscope_asr.py`
- **.test_build_payload_includes_file_url()** (4 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_rejects_local_file_path()** (4 connections) — `tests/contracts/test_dashscope_tools.py`
- **._is_public_url()** (4 connections) — `tools/analysis/dashscope_asr.py`
- **._json_or_raise()** (4 connections) — `tools/analysis/dashscope_asr.py`
- **._raise_for_error()** (4 connections) — `tools/analysis/dashscope_asr.py`
- **._safe_error()** (4 connections) — `tools/analysis/dashscope_asr.py`
- **.test_build_payload_enables_words()** (3 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_default_enable_words_is_true()** (3 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_default_model_is_filetrans()** (3 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_extract_words_normalizes_ms_to_seconds()** (3 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_rejects_empty_url()** (3 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_rejects_no_key()** (3 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_rejects_relative_path()** (3 connections) — `tests/contracts/test_dashscope_tools.py`
- **.estimate_cost()** (3 connections) — `tools/analysis/dashscope_asr.py`
- **.test_default_language_hints_includes_zh_en()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_execution_mode_is_async()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- **.test_extract_words_handles_empty_transcription()** (2 connections) — `tests/contracts/test_dashscope_tools.py`
- *... and 13 more nodes in this community*

## Relationships

- [Tool Testing](Tool_Testing.md) (8 shared connections)
- [DashScope API Testing](DashScope_API_Testing.md) (4 shared connections)
- [Core Utilities](Core_Utilities.md) (4 shared connections)
- [Character Animation](Character_Animation.md) (3 shared connections)
- [Tool Execution](Tool_Execution.md) (2 shared connections)

## Source Files

- `tests/contracts/test_dashscope_tools.py`
- `tools/analysis/dashscope_asr.py`

## Audit Trail

- EXTRACTED: 79 (81%)
- INFERRED: 18 (19%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*