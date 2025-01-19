# Go Slice Modification During Iteration

This repository demonstrates a common subtle bug in Go related to modifying a slice while iterating over it using a `for range` loop. The code appends elements to the slice during iteration, leading to unexpected results. The solution illustrates a safe way to modify slices while iterating.