# Corpus Indexing System

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

- [Video Clip Similarity Search](Video_Clip_Similarity_Search.md) (7 shared connections)
- [Tool Execution](Tool_Execution.md) (5 shared connections)
- [Corpus Builder Testing](Corpus_Builder_Testing.md) (4 shared connections)
- [Clip Corpus Tests](Clip_Corpus_Tests.md) (3 shared connections)
- [Clip Similarity Operations](Clip_Similarity_Operations.md) (2 shared connections)
- [Corpus Builder Tests](Corpus_Builder_Tests.md) (2 shared connections)
- [Stock Source Protocol](Stock_Source_Protocol.md) (2 shared connections)
- [Streaming Tests](Streaming_Tests.md) (2 shared connections)
- [Tool Testing](Tool_Testing.md) (1 shared connections)
- [Clip Cache](Clip_Cache.md) (1 shared connections)
- [CLIP Embedding Tool](CLIP_Embedding_Tool.md) (1 shared connections)
- [Character Animation](Character_Animation.md) (1 shared connections)

## Source Files

- `lib/corpus.py`
- `tools/video/corpus_builder.py`

## Audit Trail

- EXTRACTED: 60 (86%)
- INFERRED: 10 (14%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*