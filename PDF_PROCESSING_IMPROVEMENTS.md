### 1. ✅ Replaced Legacy Grid Refresh Calls

**Problem**: After PDFModal submission, the legacy `getAGgrid()` helper would fail.

**Solution**: Dispatch React grid refresh events instead (via `refreshGrid()`) and rely on WebSocket auto-refresh.
