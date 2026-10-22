# ToolResult

> God node · 540 connections · `tools/base_tool.py`

**Community:** [Character Animation Tests](Character_Animation_Tests.md)

## Connections by Relation

### calls
- generate_wan() `EXTRACTED`
- generate_local_video() `EXTRACTED`
- test_character_renderer_can_handoff_to_video_compose() `EXTRACTED`
- _oom_aware_error() `EXTRACTED`
- .execute() `EXTRACTED`
- .execute() `EXTRACTED`
- .execute() `EXTRACTED`
- test_video_selector_prefers_official_provider_without_fal_upload() `EXTRACTED`
- generate_heygen_video() `EXTRACTED`
- test_image_selector_prefers_official_provider() `EXTRACTED`
- test_tts_selector_prefers_kling_official() `EXTRACTED`
- test_execute_allows_i2v_for_5b_variant() `EXTRACTED`
- test_image_selector_maps_shared_reference_input() `EXTRACTED`
- test_hyperframes_render_resolves_relative_output_path_once() `EXTRACTED`
- .test_video_selector_routes_to_hunyuan_cloud() `EXTRACTED`
- test_tts_selector_routes_to_fal_provider() `EXTRACTED`
- test_hyperframes_render_existing_preserves_authored_entry() `EXTRACTED`
- test_video_compose_routes_empty_cut_atelier_to_existing_workspace() `EXTRACTED`
- ._run_job() `EXTRACTED`
- .execute() `EXTRACTED`
- *…and 21 more `calls` connection(s) not listed (lowest-degree first to go)*

### contains
- base_tool.py `EXTRACTED`

### imports
- test_hyperframes_compose.py `EXTRACTED`
- test_phase0_contracts.py `EXTRACTED`
- video_compose.py `EXTRACTED`
- test_hunyuan_image.py `EXTRACTED`
- _shared.py `EXTRACTED`
- test_base_tool_cache.py `EXTRACTED`
- test_phase1_contracts.py `EXTRACTED`
- kling_official_image.py `EXTRACTED`
- kling_official_video.py `EXTRACTED`
- kling_avatar.py `EXTRACTED`
- kling_lip_sync.py `EXTRACTED`
- corpus_builder.py `EXTRACTED`
- test_phase2_contracts.py `EXTRACTED`
- kling_tts.py `EXTRACTED`
- _wan_engine.py `EXTRACTED`
- direct_clip_search.py `EXTRACTED`
- test_character_animation_pipeline.py `EXTRACTED`
- fal_media.py `EXTRACTED`
- schema_media.py `EXTRACTED`
- test_hunyuan_cloud_video.py `EXTRACTED`
- *…and 125 more `imports` connection(s) not listed (lowest-degree first to go)*

### rationale_for
- Standard result returned by tool execution. `EXTRACTED`

### references
- .execute() `EXTRACTED`
- .execute() `EXTRACTED`
- .execute() `EXTRACTED`
- .execute() `EXTRACTED`
- .execute() `EXTRACTED`
- .execute() `EXTRACTED`
- .execute() `EXTRACTED`
- .execute() `EXTRACTED`
- ._remotion_render() `EXTRACTED`
- ._render() `EXTRACTED`
- .execute() `EXTRACTED`
- .execute() `EXTRACTED`
- .execute() `EXTRACTED`
- .execute() `EXTRACTED`
- ._stitch() `EXTRACTED`
- .execute() `EXTRACTED`
- .execute() `EXTRACTED`
- .execute() `EXTRACTED`
- ._compose() `EXTRACTED`
- ._generate() `EXTRACTED`
- *…and 190 more `references` connection(s) not listed (lowest-degree first to go)*

### uses
- VideoCompose `INFERRED`
- HunyuanCloudVideo `INFERRED`
- SeedanceArkVideo `INFERRED`
- HyperFramesCompose `INFERRED`
- JimengVideo `INFERRED`
- HunyuanImage `INFERRED`
- VideoSelector `INFERRED`
- AtlasVideo `INFERRED`
- KlingLipSync `INFERRED`
- KlingOfficialVideo `INFERRED`
- FishAudioTTS `INFERRED`
- ImageSelector `INFERRED`
- ComfyUIVideo `INFERRED`
- AzureTTS `INFERRED`
- AudioMixer `INFERRED`
- KlingOfficialImage `INFERRED`
- ElevenLabsTTS `INFERRED`
- DashscopeImage `INFERRED`
- ComfyUIMusic `INFERRED`
- DashscopeAsr `INFERRED`
- *…and 122 more `uses` connection(s) not listed (lowest-degree first to go)*

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*