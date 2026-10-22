# Network Guard Tests

> 16 nodes · cohesion 0.12

## Key Concepts

- **test_network_guard.py** (10 connections) — `tests/test_network_guard.py`
- **TestPaidToolsCannotSpend** (6 connections) — `tests/test_network_guard.py`
- **TestGuardBlocksOutbound** (5 connections) — `tests/test_network_guard.py`
- **socket** (3 connections)
- **TestLiveApiMarkerIsSkipped** (2 connections) — `tests/test_network_guard.py`
- **.test_loopback_still_permitted()** (2 connections) — `tests/test_network_guard.py`
- **.test_this_should_never_run_by_default()** (2 connections) — `tests/test_network_guard.py`
- **.test_atlas_image_fails_instead_of_billing()** (2 connections) — `tests/test_network_guard.py`
- **.test_atlas_video_fails_instead_of_billing()** (2 connections) — `tests/test_network_guard.py`
- **.test_create_connection_is_blocked()** (1 connections) — `tests/test_network_guard.py`
- **.test_raw_socket_connect_is_blocked()** (1 connections) — `tests/test_network_guard.py`
- **.test_requests_cannot_reach_a_provider()** (1 connections) — `tests/test_network_guard.py`
- **live_api** (1 connections)
- **Meta-tests: prove the session network guard actually blocks paid calls. If…** (1 connections) — `tests/test_network_guard.py`
- **Local servers and fixtures must keep working.** (1 connections) — `tests/test_network_guard.py`
- **The guard must hold even with a real key present in the environment.** (1 connections) — `tests/test_network_guard.py`

## Relationships

- [Atlas Image Routes](Atlas_Image_Routes.md) (3 shared connections)
- [Atlas Video Provider Tests](Atlas_Video_Provider_Tests.md) (3 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (2 shared connections)
- [Project Init Validation](Project_Init_Validation.md) (1 shared connections)
- [Test Network Guard](Test_Network_Guard.md) (1 shared connections)
- [Kling Client Tests](Kling_Client_Tests.md) (1 shared connections)

## Source Files

- `tests/test_network_guard.py`

## Audit Trail

- EXTRACTED: 24 (92%)
- INFERRED: 2 (8%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*