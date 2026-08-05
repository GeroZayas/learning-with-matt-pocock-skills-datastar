# Learning Record 0006: Using the Official `datastar-py` SDK with FastAPI

- **Date:** 2026-08-05
- **Topic:** Official Datastar Python SDK (`datastar-py`), `datastar_py.fastapi` helpers (`DatastarResponse`, `@datastar_response`, `read_signals`), and `ServerSentEventGenerator`.
- **Key Insights:**
  - The official SDK provides dedicated FastAPI integration (`datastar_py.fastapi`).
  - `@datastar_response` decorates FastAPI route handlers to return SSE responses seamlessly.
  - `read_signals(request)` correctly parses incoming signals sent by Datastar frontend actions.
  - `SSE.patch_elements()` generates properly formatted event payloads (`datastar-patch-elements`) conforming to the official Datastar protocol.
- **Next Steps:** Review official SDK reference and apply `datastar-py` in Python backend implementations.
