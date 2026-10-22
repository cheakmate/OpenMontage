# Documentary Governance Tests

> 21 nodes · cohesion 0.13

## Key Concepts

- **CorpusBuilder** (27 connections) — `tools/video/corpus_builder.py`
- **test_documentary_governance.py** (25 connections) — `tests/tools/test_documentary_governance.py`
- **_DummySource** (8 connections) — `tests/tools/test_documentary_governance.py`
- **test_corpus_builder_reports_source_level_discoverability()** (6 connections) — `tests/tools/test_documentary_governance.py`
- **.get_info()** (6 connections) — `tools/video/corpus_builder.py`
- **.get_status()** (5 connections) — `tools/video/corpus_builder.py`
- **test_corpus_builder_rejects_unavailable_pinned_sources()** (3 connections) — `tests/tools/test_documentary_governance.py`
- **test_video_compose_blocks_silent_hyperframes_swap()** (3 connections) — `tests/tools/test_documentary_governance.py`
- **test_video_compose_ffmpeg_engine_reflects_path_availability()** (3 connections) — `tests/tools/test_documentary_governance.py`
- **test_video_compose_surfaces_all_three_runtimes()** (3 connections) — `tests/tools/test_documentary_governance.py`
- **Any** (3 connections)
- **.download()** (2 connections) — `tests/tools/test_documentary_governance.py`
- **test_video_compose_rejects_unknown_render_runtime()** (2 connections) — `tests/tools/test_documentary_governance.py`
- **.estimate_cost()** (2 connections) — `tools/video/corpus_builder.py`
- **.__init__()** (1 connections) — `tests/tools/test_documentary_governance.py`
- **.is_available()** (1 connections) — `tests/tools/test_documentary_governance.py`
- **.search()** (1 connections) — `tests/tools/test_documentary_governance.py`
- **Path** (1 connections)
- **Preflight must see remotion, hyperframes, and ffmpeg as separate engines.** (1 connections) — `tests/tools/test_documentary_governance.py`
- **Regression: `get_info()["render_engines"]["ffmpeg"]` must actually check…** (1 connections) — `tests/tools/test_documentary_governance.py`
- **Governance: if render_runtime='hyperframes' is locked but runtime is missing,…** (1 connections) — `tests/tools/test_documentary_governance.py`

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (19 shared connections)
- [Cinematic Remotion Adapter](Cinematic_Remotion_Adapter.md) (6 shared connections)
- [Stock Source Protocol](Stock_Source_Protocol.md) (4 shared connections)
- [ComfyUI Setup Registry](ComfyUI_Setup_Registry.md) (3 shared connections)
- [Corpus Path Safety](Corpus_Path_Safety.md) (3 shared connections)
- [Corpus Builder Failure Tests](Corpus_Builder_Failure_Tests.md) (3 shared connections)
- [Clip Corpus](Clip_Corpus.md) (3 shared connections)
- [Stock Media Search](Stock_Media_Search.md) (3 shared connections)
- [CLIP Embedder](CLIP_Embedder.md) (1 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (1 shared connections)
- [Clip Similarity Search](Clip_Similarity_Search.md) (1 shared connections)
- [Image Selector Tests](Image_Selector_Tests.md) (1 shared connections)

## Source Files

- `tests/tools/test_documentary_governance.py`
- `tools/video/corpus_builder.py`

## Audit Trail

- EXTRACTED: 64 (82%)
- INFERRED: 14 (18%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*