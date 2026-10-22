# Clip Similarity Search

> 14 nodes · cohesion 0.16

## Key Concepts

- **ClipRecord** (16 connections) — `lib/corpus.py`
- **.rank_by_text()** (5 connections) — `lib/corpus.py`
- **.add()** (4 connections) — `lib/corpus.py`
- **._fused_sims()** (4 connections) — `lib/corpus.py`
- **.find_similar_set()** (3 connections) — `lib/corpus.py`
- **.knn()** (3 connections) — `lib/corpus.py`
- **ndarray** (3 connections)
- **.get()** (2 connections) — `lib/corpus.py`
- **Append a new clip to the corpus. Idempotent by clip_id.** (1 connections) — `lib/corpus.py`
- **Cosine similarity fused across visual and tag channels. Both embedding banks…** (1 connections) — `lib/corpus.py`
- **Return the top-k records scored against an embedded text query. Args:…** (1 connections) — `lib/corpus.py`
- **Pure k-nearest-neighbours against the visual channel only. Used as a building…** (1 connections) — `lib/corpus.py`
- **Collection-style retrieval: `n` clips that share the seed's visual register but…** (1 connections) — `lib/corpus.py`
- **One row in the corpus index. Fields mirror everything we want to query or…** (1 connections) — `lib/corpus.py`

## Relationships

- [Clip Corpus](Clip_Corpus.md) (7 shared connections)
- [Corpus Diversify Tests](Corpus_Diversify_Tests.md) (3 shared connections)
- [Corpus Path Safety](Corpus_Path_Safety.md) (3 shared connections)
- [CLIP Embedder](CLIP_Embedder.md) (1 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (1 shared connections)
- [Documentary Governance Tests](Documentary_Governance_Tests.md) (1 shared connections)

## Source Files

- `lib/corpus.py`

## Audit Trail

- EXTRACTED: 30 (97%)
- INFERRED: 1 (3%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*