# Atlas Cloud Client

> 21 nodes · cohesion 0.19

## Key Concepts

- **atlas_client.py** (19 connections) — `tools/atlas_client.py`
- **poll()** (10 connections) — `tools/atlas_client.py`
- **AtlasError** (9 connections) — `tools/atlas_client.py`
- **submit()** (9 connections) — `tools/atlas_client.py`
- **upload_media()** (9 connections) — `tools/atlas_client.py`
- **download()** (7 connections) — `tools/atlas_client.py`
- **_payload_of()** (7 connections) — `tools/atlas_client.py`
- **_raise_for_status()** (7 connections) — `tools/atlas_client.py`
- **_headers()** (4 connections) — `tools/atlas_client.py`
- **Any** (4 connections)
- **aspect_ratio_from_size()** (3 connections) — `tools/atlas_client.py`
- **Path** (2 connections)
- **RuntimeError** (1 connections)
- **Shared Atlas Cloud API plumbing for the image and video provider tools. Atlas…** (1 connections) — `tools/atlas_client.py`
- **Submit a generation request and return its prediction id.** (1 connections) — `tools/atlas_client.py`
- **Poll a prediction until it terminates. Returns the final `data` object. Raises…** (1 connections) — `tools/atlas_client.py`
- **Upload a local file and return the hosted URL Atlas assigns to it. Used to turn…** (1 connections) — `tools/atlas_client.py`
- **Download a generated asset to disk and return the written path.** (1 connections) — `tools/atlas_client.py`
- **Pick the closest ratio in `allowed` to width/height. OpenMontage's canonical…** (1 connections) — `tools/atlas_client.py`
- **Raised for any Atlas Cloud API or transport failure.** (1 connections) — `tools/atlas_client.py`
- **Parse an Atlas envelope, raising AtlasError with the body on any problem. Atlas…** (1 connections) — `tools/atlas_client.py`

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (8 shared connections)
- [Atlas Image Routes](Atlas_Image_Routes.md) (6 shared connections)
- [Seedance Payload Builder](Seedance_Payload_Builder.md) (4 shared connections)
- [Atlas Video Provider Tests](Atlas_Video_Provider_Tests.md) (1 shared connections)

## Source Files

- `tools/atlas_client.py`

## Audit Trail

- EXTRACTED: 59 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*