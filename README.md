# Cashe LRU Simulation
## How it works
The User inputs the cache description as well as the cache.
This page then uses JavaScript to Simulate the application of an LRU Cache.
For each memory access in the input, the page will print a 'C' if it is served by the cache, and print 'M' if it is served by the memory.
## How to use it. 
The first line of the input is used to describe the cache. Using the Example A

- 32 = W
- 1024 = C
- 64 = B
- 4 = k


#### Definitions

- **W** is the number of bits in one word. This number will be a multiple of 8
- **C** is the number of data bytes in the cache. This number will be a power of 2. (In C, we do not count the space needed to store tags, just the space needed to store data.)
- **B** is the number of bytes in one cache block. This number will be a divisor of C.
- **k** is the number of lines in a block. This number will be a divisor of B.

#### Example A Input
32 1024 64 4

409

658

915

1172

661

1429

1168

403

925

1172


#### Example A Output


MMMM

CMCM

MC


**Load of the actual index.html for more detailed instructions.**

#### Taks To Do
[x] Fix Bug
[] Finish CSS
[] Finish Direct Mapping
[] Finish Fully Associative
