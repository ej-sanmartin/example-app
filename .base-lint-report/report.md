<!-- base-lint-sticky -->
## Base Lint Report

**Status:** ❌ Limited: 2 · ⚠️ Newly: 1 · ✅ Widely: 0

| File | Line | Feature | Baseline | Guidance |
|------|------|---------|----------|----------|
| src/app.tsx | 3 | navigator.share() | Limited | Provide fallback UI or feature detection for unsupported browsers. |
| src/app.tsx | 4 | navigator.share() | Limited | Provide fallback UI or feature detection for unsupported browsers. |
| src/styles.css | 1 | :has() | Newly | OK for modern targets; keep a fallback in place for older browsers. |

Policy: Limited = error (max 0), Newly = warn (non-blocking)
Dataset: web-features 2.49.0