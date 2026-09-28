# Data Structures Assignment - Question 5

## Problem

A company has the hierarchy:

- CFO -> HR, Finance, IT
- IT -> Development, Testing
- Development -> Frontend, Backend

### Tasks completed

1. Represented the hierarchy using a general tree with first-child/next-sibling representation.
2. Constructed the tree in C.
3. Displayed the hierarchy using level-order traversal.
4. Stored department names in an array for searching.
5. Compared Linear Search and Binary Search.
6. Recorded comparison counts for three searches.
7. Analysed tree height, traversal behaviour, search comparisons, and time/space complexity.
8. Included trace table, comparison table, complexity analysis, output, input, and final conclusion.

## Files

- `src/organization_hierarchy.c` - C source code
- `input/input.txt` - input/problem data
- `output/output.txt` - executed program output
- `trace/trace_table.md` - intermediate trace table
- `docs/comparison_table.md` - search comparison table
- `docs/complexity_analysis.md` - time and space complexity
- `docs/final_conclusion.md` - final conclusion

## Compilation and execution

```bash
gcc src/organization_hierarchy.c -o organization_hierarchy
./organization_hierarchy
```

On Windows with MinGW GCC:

```text
gcc src/organization_hierarchy.c -o organization_hierarchy.exe
organization_hierarchy.exe
```

## Expected level-order output

`CFO HR Finance IT Development Testing Frontend Backend`
