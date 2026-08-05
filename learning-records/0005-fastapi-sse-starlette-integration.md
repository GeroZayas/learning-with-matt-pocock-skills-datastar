# Learning Record 0005: FastAPI & SSE Starlette Integration with Datastar

- **Date:** 2026-08-05
- **Topic:** Correct FastAPI Server-Sent Events implementation using `sse-starlette` (`EventSourceResponse`) alongside Datastar.
- **Key Insights:**
  - Using `sse-starlette` (`EventSourceResponse`) provides production-grade handling for SSE streams in FastAPI, automatically managing client disconnects and keep-alives.
  - Datastar expects SSE messages formatted with `event: datastar-patch-dom` and `data: fragments <html...>` (or dictionaries yielding `event` and `data` in `sse-starlette`).
  - GET requests from Datastar transmit signals via query parameters, which FastAPI can easily validate and parse.
- **Next Steps:** Review SDK reference and apply `sse-starlette` in your FastAPI server scripts.
