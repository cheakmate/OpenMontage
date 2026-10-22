# Image Generation Tests

> 15 nodes · cohesion 0.20

## Key Concepts

- **.execute()** (15 connections) — `tools/graphics/google_imagen.py`
- **._execute_gemini()** (9 connections) — `tools/graphics/google_imagen.py`
- **.estimate_cost()** (7 connections) — `tools/graphics/google_imagen.py`
- **._output_paths()** (6 connections) — `tools/graphics/google_imagen.py`
- **._resolve_aspect_ratio()** (6 connections) — `tools/graphics/google_imagen.py`
- **test_artifacts_match_billed_image_count()** (4 connections) — `tests/tools/test_google_imagen_multi_output.py`
- **Any** (4 connections)
- **test_multi_output_paths_are_suffixed_and_unique()** (3 connections) — `tests/tools/test_google_imagen_multi_output.py`
- **_dims_to_aspect_ratio()** (3 connections) — `tools/graphics/google_imagen.py`
- **._get_api_key()** (2 connections) — `tools/graphics/google_imagen.py`
- **Path** (1 connections)
- **Derive one output path per generated image. With a single image, honor the…** (1 connections) — `tools/graphics/google_imagen.py`
- **Explicit aspect_ratio > derived from width/height > default 1:1.** (1 connections) — `tools/graphics/google_imagen.py`
- **Generate via a Gemini image model (e.g. gemini-2.5-flash-image). These models…** (1 connections) — `tools/graphics/google_imagen.py`
- **Convert width/height to the nearest supported aspect ratio.** (1 connections) — `tools/graphics/google_imagen.py`

## Relationships

- [Tool Contracts](Tool_Contracts.md) (12 shared connections)
- [Google Imagen Tests](Google_Imagen_Tests.md) (4 shared connections)
- [Character Animation](Character_Animation.md) (2 shared connections)
- [Project Init](Project_Init.md) (1 shared connections)
- [Core Utilities](Core_Utilities.md) (1 shared connections)
- [Google Imagen Testing](Google_Imagen_Testing.md) (1 shared connections)
- [Video Tool Tests](Video_Tool_Tests.md) (1 shared connections)

## Source Files

- `tests/tools/test_google_imagen_multi_output.py`
- `tools/graphics/google_imagen.py`

## Audit Trail

- EXTRACTED: 37 (86%)
- INFERRED: 6 (14%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*