# Learning Record 0003: Signals, Binding, & User Input with FastAPI

- **Date:** 2026-08-05
- **Topic:** Two-way signal binding (`data-bind-*`), event debouncing (`__debounce`), and handling user inputs in FastAPI.
- **Key Insights:**
  - Datastar makes binding form controls to reactive state effortless using `data-bind-<signalName>`.
  - Combining input bindings with event modifiers like `__debounce.300ms` ensures high performance by preventing excessive backend requests during fast typing.
  - FastAPI can easily extract query parameters or signal payloads and stream back targeted DOM patches via SSE.
- **Next Steps:** Proceed to Lesson 4 to build a complete interactive CRUD / List Filtering component using Datastar + FastAPI.
