---
category: minorAnalysis
---
* The query `go/incorrect-integer-conversion` now correctly recognizes more guards of the form `if val <= x` to protect a conversion `uintX(val)`.
