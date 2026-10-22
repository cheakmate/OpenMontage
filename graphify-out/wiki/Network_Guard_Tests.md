# Network Guard Tests

> 18 nodes · cohesion 0.17

## Key Concepts

- **tests/conftest.py** (11 connections) — `tests/conftest.py`
- **_block_network()** (7 connections) — `tests/conftest.py`
- **_blocked()** (5 connections) — `tests/conftest.py`
- **_is_loopback()** (5 connections) — `tests/conftest.py`
- **NetworkCallInTestError** (4 connections) — `tests/conftest.py`
- **guarded_connect()** (3 connections) — `tests/conftest.py`
- **guarded_connect_ex()** (3 connections) — `tests/conftest.py`
- **guarded_create_connection()** (3 connections) — `tests/conftest.py`
- **_network_allowed()** (3 connections) — `tests/conftest.py`
- **pytest_collection_modifyitems()** (3 connections) — `tests/conftest.py`
- **pytest_configure()** (1 connections) — `tests/conftest.py`
- **fixture** (1 connections)
- **RuntimeError** (1 connections)
- **Session-wide test safety net. **No test may open a network connection.**…** (1 connections) — `tests/conftest.py`
- **Skip live_api tests unless the operator explicitly opted in.** (1 connections) — `tests/conftest.py`
- **Raised when a test tries to open a non-loopback connection.** (1 connections) — `tests/conftest.py`
- **True for loopback TCP/UDP targets and for AF_UNIX socket paths.** (1 connections) — `tests/conftest.py`
- **Refuse non-loopback sockets for the entire session.** (1 connections) — `tests/conftest.py`

## Relationships

- [Tool Testing](Tool_Testing.md) (1 shared connections)
- [Live API Tests](Live_API_Tests.md) (1 shared connections)
- [Project Init](Project_Init.md) (1 shared connections)

## Source Files

- `tests/conftest.py`

## Audit Trail

- EXTRACTED: 26 (90%)
- INFERRED: 3 (10%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*