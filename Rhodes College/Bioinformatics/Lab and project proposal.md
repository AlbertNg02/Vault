


Dataset: 1000 genome dataset

Approches to DNA Seq Analysis

1. De novo asembly - build original underlying sequence from set of reads

2. Resesuqncing Approches - align reads to reference genome


```denovo example
you have to know
take? i can

```


Shortest common subperstring problem

- Input: string s1, s2, s3, sm
- Output: A string S that contains s1,s2...sn and has min length
- Note: we are not considering erros
- **DP with 2 strings**: O(mn) where m + n are lengths of 2 strings

**Greedy Algorithm for SCS** 
- Find pair of strings (si, sj) with longest overlap. How? ( suffix trees, DP)
- Merge si and sj
- Repeat (one fewer read)
- Stop when one read left

Ex:
```
Combine overlap(combine pair of largest overlap)
```

