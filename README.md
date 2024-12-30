# Uninitialized Map Access in Go

This repository demonstrates a common error in Go: accessing elements of an uninitialized map.  Attempting to read or write to a map that hasn't been created results in a runtime panic.

The `bug.go` file shows the erroneous code, while `bugSolution.go` provides the corrected version.

**Key takeaway**: Always initialize maps in Go before using them to prevent unexpected panics.