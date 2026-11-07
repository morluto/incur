---
'incur': patch
---

Fixed option and environment coercion for Zod 4 numeric formats such as `z.int()`, `z.int32()`, `z.uint32()`, `z.float32()`, and `z.float64()`. Decimal strings are coerced with `Number()` before the original schema checks format, range, and refinements.
