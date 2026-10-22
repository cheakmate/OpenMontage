# Source Adapter Availability

> 3 nodes · cohesion 0.67

## Key Concepts

- **available_sources()** (10 connections) — `tools/video/stock_sources/__init__.py`
- **.get_status()** (3 connections) — `tools/video/direct_clip_search.py`
- **Return only the adapters whose `is_available()` is True. This is what the…** (1 connections) — `tools/video/stock_sources/__init__.py`

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (4 shared connections)
- [Stock Source Protocol](Stock_Source_Protocol.md) (3 shared connections)
- [Clip Corpus](Clip_Corpus.md) (1 shared connections)
- [Documentary Governance Tests](Documentary_Governance_Tests.md) (1 shared connections)
- [Download Timeout Regression](Download_Timeout_Regression.md) (1 shared connections)

## Source Files

- `tools/video/direct_clip_search.py`
- `tools/video/stock_sources/__init__.py`

## Audit Trail

- EXTRACTED: 11 (92%)
- INFERRED: 1 (8%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*