# Image Multi-Output Tests

> 18 nodes · cohesion 0.16

## Key Concepts

- **test_openai_image_multi_output.py** (15 connections) — `tests/tools/test_openai_image_multi_output.py`
- **.execute()** (8 connections) — `tools/graphics/openai_image.py`
- **.estimate_cost()** (5 connections) — `tools/graphics/openai_image.py`
- **._output_paths()** (5 connections) — `tools/graphics/openai_image.py`
- **test_artifacts_match_billed_image_count()** (4 connections) — `tests/tools/test_openai_image_multi_output.py`
- **_FakeImage** (3 connections) — `tests/tools/test_openai_image_multi_output.py`
- **_FakeImages** (3 connections) — `tests/tools/test_openai_image_multi_output.py`
- **_FakeResponse** (3 connections) — `tests/tools/test_openai_image_multi_output.py`
- **test_multi_output_paths_are_suffixed_and_unique()** (3 connections) — `tests/tools/test_openai_image_multi_output.py`
- **.generate()** (2 connections) — `tests/tools/test_openai_image_multi_output.py`
- **.__init__()** (2 connections) — `tests/tools/test_openai_image_multi_output.py`
- **test_all_requested_images_are_written()** (2 connections) — `tests/tools/test_openai_image_multi_output.py`
- **test_single_image_keeps_exact_output_path()** (2 connections) — `tests/tools/test_openai_image_multi_output.py`
- **Any** (2 connections)
- **.__init__()** (1 connections) — `tests/tools/test_openai_image_multi_output.py`
- **Path** (1 connections)
- **Regression tests: openai_image must return every image it requests and bills…** (1 connections) — `tests/tools/test_openai_image_multi_output.py`
- **Derive one output path per generated image. With a single image, honor the…** (1 connections) — `tools/graphics/openai_image.py`

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (6 shared connections)
- [Imagen Gemini Backend](Imagen_Gemini_Backend.md) (2 shared connections)
- [Project Init Validation](Project_Init_Validation.md) (2 shared connections)
- [TTS Provider Tests](TTS_Provider_Tests.md) (2 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (1 shared connections)
- [Lyria BGM Generator](Lyria_BGM_Generator.md) (1 shared connections)
- [Cinematic Scene Types](Cinematic_Scene_Types.md) (1 shared connections)

## Source Files

- `tests/tools/test_openai_image_multi_output.py`
- `tools/graphics/openai_image.py`

## Audit Trail

- EXTRACTED: 34 (87%)
- INFERRED: 5 (13%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*