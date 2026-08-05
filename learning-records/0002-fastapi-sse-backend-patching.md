# Learning Record 0002: Server-Sent Events & FastAPI Backend Patching

- **Date:** 2026-08-05
- **Topic:** FastAPI `StreamingResponse`, SSE protocol for Datastar (`datastar-patch-dom`), and server-driven DOM updates.
- **Key Insights:**
  - Datastar relies on Server-Sent Events (SSE) where the event type is `datastar-patch-dom` and the data payload includes HTML fragments.
  - FastAPI handles this cleanly using async generators and `StreamingResponse(..., media_type="text/event-stream")`.
  - This architecture keeps state on the server or syncs via signals while the DOM is continuously patched over an open stream.
- **Next Steps:** Proceed to Lesson 3 to build an interactive form with real-time signal binding and validation.
