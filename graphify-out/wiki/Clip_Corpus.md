# Clip Corpus

> 20 nodes · cohesion 0.19

## Key Concepts

- **Corpus** (32 connections) — `lib/corpus.py`
- **.execute()** (17 connections) — `tools/video/corpus_builder.py`
- **.load()** (8 connections) — `lib/corpus.py`
- **.save()** (7 connections) — `lib/corpus.py`
- **.ensure_dirs()** (6 connections) — `lib/corpus.py`
- **Path** (6 connections)
- **.embed_path()** (4 connections) — `lib/corpus.py`
- **.index_path()** (4 connections) — `lib/corpus.py`
- **.tag_embed_path()** (4 connections) — `lib/corpus.py`
- **.clips_dir()** (3 connections) — `lib/corpus.py`
- **.thumbs_dir()** (3 connections) — `lib/corpus.py`
- **.diversify()** (2 connections) — `lib/corpus.py`
- **.has()** (2 connections) — `lib/corpus.py`
- **.__init__()** (2 connections) — `lib/corpus.py`
- **filters_for()** (2 connections) — `tools/video/corpus_builder.py`
- **.__len__()** (1 connections) — `lib/corpus.py`
- **Load existing corpus from disk. Silently starts empty if absent.** (1 connections) — `lib/corpus.py`
- **Persist index + both embedding stacks atomically-ish.** (1 connections) — `lib/corpus.py`
- **Given a pre-selected candidate list, greedily pick `n` that are mutually…** (1 connections) — `lib/corpus.py`
- **Append-only local clip corpus with vector search. Usage:: corp =…** (1 connections) — `lib/corpus.py`

## Relationships

- [Clip Similarity Search](Clip_Similarity_Search.md) (7 shared connections)
- [Corpus Path Safety](Corpus_Path_Safety.md) (4 shared connections)
- [Corpus Diversify Tests](Corpus_Diversify_Tests.md) (3 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (3 shared connections)
- [Documentary Governance Tests](Documentary_Governance_Tests.md) (3 shared connections)
- [Stock Source Protocol](Stock_Source_Protocol.md) (3 shared connections)
- [Clip Retrieval Operations](Clip_Retrieval_Operations.md) (2 shared connections)
- [Corpus Builder Failure Tests](Corpus_Builder_Failure_Tests.md) (2 shared connections)
- [Source Adapter Availability](Source_Adapter_Availability.md) (1 shared connections)
- [Clip Cache Tests](Clip_Cache_Tests.md) (1 shared connections)
- [CLIP Embedder](CLIP_Embedder.md) (1 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (1 shared connections)

## Source Files

- `lib/corpus.py`
- `tools/video/corpus_builder.py`

## Audit Trail

- EXTRACTED: 60 (86%)
- INFERRED: 10 (14%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*