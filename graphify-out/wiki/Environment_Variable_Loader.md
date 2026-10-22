# Environment Variable Loader

> 23 nodes · cohesion 0.09

## Key Concepts

- **test_05_video_compose.py** (14 connections) — `tests/qa/test_05_video_compose.py`
- **env_loader.py** (13 connections) — `lib/env_loader.py`
- **load_env()** (8 connections) — `lib/env_loader.py`
- **ensure_audio()** (3 connections) — `tests/qa/test_05_video_compose.py`
- **ensure_image()** (3 connections) — `tests/qa/test_05_video_compose.py`
- **ensure_video()** (3 connections) — `tests/qa/test_05_video_compose.py`
- **test_env_example.py** (3 connections) — `tests/contracts/test_env_example.py`
- **get_env()** (2 connections) — `lib/env_loader.py`
- **require_env()** (2 connections) — `lib/env_loader.py`
- **test_env_example_does_not_turn_comments_into_credentials()** (2 connections) — `tests/contracts/test_env_example.py`
- **ensure_subtitle()** (2 connections) — `tests/qa/test_05_video_compose.py`
- **dotenv** (2 connections)
- **Path** (1 connections)
- **Environment variable loader for OpenMontage. Loads .env file and provides typed…** (1 connections) — `lib/env_loader.py`
- **Load .env file from project root.** (1 connections) — `lib/env_loader.py`
- **Get an environment variable with optional default.** (1 connections) — `lib/env_loader.py`
- **Get a required environment variable. Raises if missing.** (1 connections) — `lib/env_loader.py`
- **A fresh copy of .env.example must leave every documented key unset.** (1 connections) — `tests/contracts/test_env_example.py`
- **QA Test 05: Video composition — image + mixed audio → video, verify A/V sync.…** (1 connections) — `tests/qa/test_05_video_compose.py`
- **Generate a test image with ffmpeg if it doesn't exist.** (1 connections) — `tests/qa/test_05_video_compose.py`
- **Generate a test video clip with ffmpeg if it doesn't exist. Uses forced…** (1 connections) — `tests/qa/test_05_video_compose.py`
- **Generate a test audio file if it doesn't exist.** (1 connections) — `tests/qa/test_05_video_compose.py`
- **Write a minimal SRT subtitle file.** (1 connections) — `tests/qa/test_05_video_compose.py`

## Relationships

- [Core Utilities](Core_Utilities.md) (7 shared connections)
- [Audio Mixing](Audio_Mixing.md) (6 shared connections)
- [Tool Testing](Tool_Testing.md) (3 shared connections)
- [Kling Video Tool Tests](Kling_Video_Tool_Tests.md) (2 shared connections)
- [Pipeline Checkpoints](Pipeline_Checkpoints.md) (2 shared connections)
- [Video Composition](Video_Composition.md) (1 shared connections)
- [Lyria BGM Generation](Lyria_BGM_Generation.md) (1 shared connections)

## Source Files

- `lib/env_loader.py`
- `tests/contracts/test_env_example.py`
- `tests/qa/test_05_video_compose.py`

## Audit Trail

- EXTRACTED: 45 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*