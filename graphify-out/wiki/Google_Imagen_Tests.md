# Google Imagen Tests

> 30 nodes · cohesion 0.11

## Key Concepts

- **GoogleImagen** (30 connections) — `tools/graphics/google_imagen.py`
- **.execute()** (15 connections) — `tools/graphics/google_imagen.py`
- **test_google_imagen_multi_output.py** (12 connections) — `tests/tools/test_google_imagen_multi_output.py`
- **._execute_gemini()** (9 connections) — `tools/graphics/google_imagen.py`
- **.estimate_cost()** (7 connections) — `tools/graphics/google_imagen.py`
- **._output_paths()** (6 connections) — `tools/graphics/google_imagen.py`
- **._resolve_aspect_ratio()** (6 connections) — `tools/graphics/google_imagen.py`
- **_FakeResponse** (5 connections) — `tests/tools/test_google_imagen_multi_output.py`
- **imagen_tool()** (5 connections) — `tests/tools/test_google_imagen_multi_output.py`
- **TestGoogleImagen** (4 connections) — `tests/contracts/test_phase3_contracts.py`
- **test_artifacts_match_billed_image_count()** (4 connections) — `tests/tools/test_google_imagen_multi_output.py`
- **Any** (4 connections)
- **test_multi_output_paths_are_suffixed_and_unique()** (3 connections) — `tests/tools/test_google_imagen_multi_output.py`
- **_dims_to_aspect_ratio()** (3 connections) — `tools/graphics/google_imagen.py`
- **.test_capabilities()** (2 connections) — `tests/contracts/test_phase3_contracts.py`
- **.test_identity()** (2 connections) — `tests/contracts/test_phase3_contracts.py`
- **_post()** (2 connections) — `tests/tools/test_google_imagen_multi_output.py`
- **test_all_requested_images_are_written()** (2 connections) — `tests/tools/test_google_imagen_multi_output.py`
- **test_single_image_keeps_exact_output_path()** (2 connections) — `tests/tools/test_google_imagen_multi_output.py`
- **._get_api_key()** (2 connections) — `tools/graphics/google_imagen.py`
- **.__init__()** (1 connections) — `tests/tools/test_google_imagen_multi_output.py`
- **.json()** (1 connections) — `tests/tools/test_google_imagen_multi_output.py`
- **.raise_for_status()** (1 connections) — `tests/tools/test_google_imagen_multi_output.py`
- **fixture** (1 connections)
- **Path** (1 connections)
- *... and 5 more nodes in this community*

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (17 shared connections)
- [Imagen Gemini Backend](Imagen_Gemini_Backend.md) (5 shared connections)
- [TTS Provider Tests](TTS_Provider_Tests.md) (3 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (3 shared connections)
- [Google TTS Tests](Google_TTS_Tests.md) (2 shared connections)
- [Project Init Validation](Project_Init_Validation.md) (2 shared connections)
- [Cinematic Scene Types](Cinematic_Scene_Types.md) (1 shared connections)
- [Vertex Video Backend Tests](Vertex_Video_Backend_Tests.md) (1 shared connections)
- [Lyria BGM Generator](Lyria_BGM_Generator.md) (1 shared connections)

## Source Files

- `tests/contracts/test_phase3_contracts.py`
- `tests/tools/test_google_imagen_multi_output.py`
- `tools/graphics/google_imagen.py`

## Audit Trail

- EXTRACTED: 65 (76%)
- INFERRED: 20 (24%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*