# Clip Retrieval Operations

> 13 nodes · cohesion 0.22

## Key Concepts

- **.execute()** (10 connections) — `tools/video/clip_search.py`
- **Any** (7 connections)
- **_op_rank_for_slot()** (5 connections) — `tools/video/clip_search.py`
- **_op_diversify()** (4 connections) — `tools/video/clip_search.py`
- **_op_find_similar_set()** (4 connections) — `tools/video/clip_search.py`
- **_op_get()** (4 connections) — `tools/video/clip_search.py`
- **_op_stats()** (4 connections) — `tools/video/clip_search.py`
- **.estimate_cost()** (2 connections) — `tools/video/clip_search.py`
- **Summary counts and per-source breakdown. Useful as a sanity check before…** (1 connections) — `tools/video/clip_search.py`
- **Embed `query_text` and return top-k clips by fused similarity. This is the…** (1 connections) — `tools/video/clip_search.py`
- **MMR-based similar-set retrieval from one seed clip.** (1 connections) — `tools/video/clip_search.py`
- **Pick the most mutually-dissimilar subset of a candidate list.** (1 connections) — `tools/video/clip_search.py`
- **Look up one clip_id and return its full record.** (1 connections) — `tools/video/clip_search.py`

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (7 shared connections)
- [Clip Corpus](Clip_Corpus.md) (2 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (1 shared connections)
- [CLIP Embedder](CLIP_Embedder.md) (1 shared connections)

## Source Files

- `tools/video/clip_search.py`

## Audit Trail

- EXTRACTED: 27 (96%)
- INFERRED: 1 (4%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*