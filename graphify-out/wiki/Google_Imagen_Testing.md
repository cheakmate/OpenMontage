# Google Imagen Testing

> 21 nodes · cohesion 0.13

## Key Concepts

- **test_google_imagen_gemini_backend.py** (16 connections) — `tests/tools/test_google_imagen_gemini_backend.py`
- **imagen_tool()** (5 connections) — `tests/tools/test_google_imagen_gemini_backend.py`
- **_FakeResponse** (4 connections) — `tests/tools/test_google_imagen_gemini_backend.py`
- **_FakeClient** (4 connections) — `tests/tools/test_openai_image_multi_output.py`
- **test_text_only_response_is_a_clear_error()** (4 connections) — `tests/tools/test_google_imagen_gemini_backend.py`
- **_FakeCandidate** (3 connections) — `tests/tools/test_google_imagen_gemini_backend.py`
- **_FakeContent** (3 connections) — `tests/tools/test_google_imagen_gemini_backend.py`
- **_FakeInline** (3 connections) — `tests/tools/test_google_imagen_gemini_backend.py`
- **_FakePart** (3 connections) — `tests/tools/test_google_imagen_gemini_backend.py`
- **generate_content()** (3 connections) — `tests/tools/test_google_imagen_gemini_backend.py`
- **test_gemini_cost_estimate_is_per_image()** (3 connections) — `tests/tools/test_google_imagen_gemini_backend.py`
- **.__init__()** (2 connections) — `tests/tools/test_google_imagen_gemini_backend.py`
- **.__init__()** (2 connections) — `tests/tools/test_google_imagen_gemini_backend.py`
- **.__init__()** (2 connections) — `tests/tools/test_google_imagen_gemini_backend.py`
- **generate_content()** (2 connections) — `tests/tools/test_google_imagen_gemini_backend.py`
- **.__init__()** (2 connections) — `tests/tools/test_openai_image_multi_output.py`
- **.__init__()** (1 connections) — `tests/tools/test_google_imagen_gemini_backend.py`
- **.__init__()** (1 connections) — `tests/tools/test_google_imagen_gemini_backend.py`
- **test_gemini_model_routes_to_generate_content()** (1 connections) — `tests/tools/test_google_imagen_gemini_backend.py`
- **fixture** (1 connections)
- **Tests for the Gemini image backend in google_imagen. Models named `gemini-*`…** (1 connections) — `tests/tools/test_google_imagen_gemini_backend.py`

## Relationships

- [Tool Contracts](Tool_Contracts.md) (4 shared connections)
- [OpenAI Multi-Output](OpenAI_Multi-Output.md) (2 shared connections)
- [Image Selector](Image_Selector.md) (2 shared connections)
- [Image Generation Tests](Image_Generation_Tests.md) (1 shared connections)
- [Project Init](Project_Init.md) (1 shared connections)
- [Lyria BGM Generation](Lyria_BGM_Generation.md) (1 shared connections)
- [Core Utilities](Core_Utilities.md) (1 shared connections)

## Source Files

- `tests/tools/test_google_imagen_gemini_backend.py`
- `tests/tools/test_openai_image_multi_output.py`

## Audit Trail

- EXTRACTED: 35 (90%)
- INFERRED: 4 (10%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*