# NLP 243 (Fall 2024) HW 2 data

This folder contains 3 files, a subset of the 1 Billion Word Benchmark's
heldout set.

Specifically, `1b_benchmark.train.tokens` is taken from sections 0-9,
`1b_benchmark.dev.tokens` is taken from sections 10 and 11, and
`1b_benchmark.test.tokens` is taken from sections 12 and 13.

To recreate this data (download the raw 1 Billion Word Benchmark and generate the split), run:

```
./subsample_1b_benchmark.sh
```
