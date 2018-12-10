# README
## Compilation instructions
The included makefile has been modified to include the flag `-pthread`. This is important.

## Parameters
NUM_ITER = 5'000'000
pop_size = 1000
mut_rate = .3
nthread  = 4

Best tour found: 5756.88
Time: 9.892s

With just 1 thread (nthread=1) the program takes 29.911s, an improvement of just over a third.
It also finds a solution of 6539.67, which is much worse.
