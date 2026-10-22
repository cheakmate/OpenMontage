# MPS Device Tests

> 55 nodes · cohesion 0.05

## Key Concepts

- **test_mps_device.py** (25 connections) — `tests/tools/test_mps_device.py`
- **Upscale** (20 connections) — `tools/enhancement/upscale.py`
- **get_torch_device()** (14 connections) — `tools/video/_shared.py`
- **._build_upsampler()** (7 connections) — `tools/enhancement/upscale.py`
- **._upscale_video()** (7 connections) — `tools/enhancement/upscale.py`
- **test_face_restore_uses_signature_guard()** (6 connections) — `tests/tools/test_mps_device.py`
- **load_diffusers_pipeline()** (6 connections) — `tools/video/_shared.py`
- **_make_pipeline_mocks()** (5 connections) — `tests/tools/test_mps_device.py`
- **test_upscale_build_upsampler_skips_device_when_unsupported()** (5 connections) — `tests/tools/test_mps_device.py`
- **test_upscale_build_upsampler_uses_signature_guard()** (5 connections) — `tests/tools/test_mps_device.py`
- **.execute()** (5 connections) — `tools/enhancement/upscale.py`
- **._get_video_fps()** (5 connections) — `tools/enhancement/upscale.py`
- **._upscale_image()** (5 connections) — `tools/enhancement/upscale.py`
- **test_load_diffusers_pipeline_cpu_uses_float32()** (4 connections) — `tests/tools/test_mps_device.py`
- **test_load_diffusers_pipeline_offload_falls_back_on_mps()** (4 connections) — `tests/tools/test_mps_device.py`
- **test_load_diffusers_pipeline_routes_to_mps()** (4 connections) — `tests/tools/test_mps_device.py`
- **mock_torch()** (3 connections) — `tests/tools/test_mps_device.py`
- **test_get_torch_device_cpu_when_mps_backend_missing()** (3 connections) — `tests/tools/test_mps_device.py`
- **test_get_torch_device_cpu_when_mps_not_built()** (3 connections) — `tests/tools/test_mps_device.py`
- **test_get_torch_device_returns_cpu_as_fallback()** (3 connections) — `tests/tools/test_mps_device.py`
- **test_get_torch_device_returns_cpu_when_torch_not_installed()** (3 connections) — `tests/tools/test_mps_device.py`
- **test_get_torch_device_returns_cuda_when_available()** (3 connections) — `tests/tools/test_mps_device.py`
- **test_get_torch_device_returns_mps_when_cuda_absent()** (3 connections) — `tests/tools/test_mps_device.py`
- **test_local_gpu_tool_mentions_apple_silicon()** (3 connections) — `tests/tools/test_mps_device.py`
- **test_upscale_install_instructions_mentions_apple_silicon()** (3 connections) — `tests/tools/test_mps_device.py`
- *... and 30 more nodes in this community*

## Relationships

- [Tool Testing](Tool_Testing.md) (9 shared connections)
- [Core Utilities](Core_Utilities.md) (7 shared connections)
- [Tool Execution](Tool_Execution.md) (3 shared connections)
- [Character Animation](Character_Animation.md) (3 shared connections)
- [FFmpeg Tests](FFmpeg_Tests.md) (2 shared connections)
- [WAN Engine](WAN_Engine.md) (2 shared connections)
- [Project Init](Project_Init.md) (1 shared connections)
- [Lyria BGM Generation](Lyria_BGM_Generation.md) (1 shared connections)
- [Visual Evaluation System](Visual_Evaluation_System.md) (1 shared connections)

## Source Files

- `tests/tools/test_mps_device.py`
- `tools/enhancement/upscale.py`
- `tools/video/_shared.py`

## Audit Trail

- EXTRACTED: 95 (87%)
- INFERRED: 14 (13%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*