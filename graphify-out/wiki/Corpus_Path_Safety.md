# Corpus Path Safety

> 22 nodes · cohesion 0.15

## Key Concepts

- **test_corpus_builder_path_traversal.py** (20 connections) — `tests/tools/test_corpus_builder_path_traversal.py`
- **test_process_candidate_rejects_traversing_clip_id()** (10 connections) — `tests/tools/test_corpus_builder_path_traversal.py`
- **_is_safe_clip_id()** (9 connections) — `tools/video/corpus_builder.py`
- **test_corpus_builder_execute_skips_and_records_unsafe_candidates()** (8 connections) — `tests/tools/test_corpus_builder_path_traversal.py`
- **DummyTraversingSource** (7 connections) — `tests/tools/test_corpus_builder_path_traversal.py`
- **_safe_child_path()** (6 connections) — `tools/video/corpus_builder.py`
- **DummyCandidate** (5 connections) — `tests/tools/test_corpus_builder_path_traversal.py`
- **Path** (4 connections)
- **mock_process_candidate()** (3 connections) — `tests/tools/test_corpus_builder_path_traversal.py`
- **test_is_safe_clip_id_accepts_valid_ids()** (3 connections) — `tests/tools/test_corpus_builder_path_traversal.py`
- **test_is_safe_clip_id_rejects_malicious_and_traversal_ids()** (3 connections) — `tests/tools/test_corpus_builder_path_traversal.py`
- **test_safe_child_path_confines_paths()** (3 connections) — `tests/tools/test_corpus_builder_path_traversal.py`
- **.download()** (2 connections) — `tests/tools/test_corpus_builder_path_traversal.py`
- **.__init__()** (2 connections) — `tests/tools/test_corpus_builder_path_traversal.py`
- **parametrize** (2 connections)
- **.clip_id()** (1 connections) — `tests/tools/test_corpus_builder_path_traversal.py`
- **.is_available()** (1 connections) — `tests/tools/test_corpus_builder_path_traversal.py`
- **.search()** (1 connections) — `tests/tools/test_corpus_builder_path_traversal.py`
- **ingest()** (1 connections) — `tests/tools/test_corpus_builder_path_traversal.py`
- **try_link()** (1 connections) — `tests/tools/test_corpus_builder_path_traversal.py`
- **Validate that clip_id cannot cause path traversal or filesystem escapes.** (1 connections) — `tools/video/corpus_builder.py`
- **Resolve a child path within parent_dir, guaranteeing no traversal.** (1 connections) — `tools/video/corpus_builder.py`

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (5 shared connections)
- [Clip Corpus](Clip_Corpus.md) (4 shared connections)
- [Clip Similarity Search](Clip_Similarity_Search.md) (3 shared connections)
- [Documentary Governance Tests](Documentary_Governance_Tests.md) (3 shared connections)
- [CLIP Embedder](CLIP_Embedder.md) (3 shared connections)
- [Video Thumbnail Extraction](Video_Thumbnail_Extraction.md) (1 shared connections)
- [Stock Source Protocol](Stock_Source_Protocol.md) (1 shared connections)
- [Lyria BGM Generator](Lyria_BGM_Generator.md) (1 shared connections)
- [Project Init Validation](Project_Init_Validation.md) (1 shared connections)
- [Corpus Diversify Tests](Corpus_Diversify_Tests.md) (1 shared connections)
- [Asset Cache Modules](Asset_Cache_Modules.md) (1 shared connections)

## Source Files

- `tests/tools/test_corpus_builder_path_traversal.py`
- `tools/video/corpus_builder.py`

## Audit Trail

- EXTRACTED: 56 (95%)
- INFERRED: 3 (5%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*