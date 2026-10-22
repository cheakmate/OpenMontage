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

- [Tool Base Runtime](Tool_Base_Runtime.md) (15 shared connections)
- [CogVideo Variant Tests](CogVideo_Variant_Tests.md) (4 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (3 shared connections)
- [Video Review Tooling](Video_Review_Tooling.md) (2 shared connections)
- [Wan Video Engine](Wan_Video_Engine.md) (2 shared connections)
- [Project Init Validation](Project_Init_Validation.md) (1 shared connections)
- [Lyria BGM Generator](Lyria_BGM_Generator.md) (1 shared connections)
- [Tool Dependency Tests](Tool_Dependency_Tests.md) (1 shared connections)

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