# While(node) vs Node.contains Benchmark

## Setup

Clone this repo and open index.html in any browser. Or visit
http://natehunzaker.com/contains-bench and do the same.

## Findings

### Chrome 49

Node.contains - yes x 16,561,750 ops/sec ±1.44% (59 runs sampled)
Node.contains - no x 15,785,211 ops/sec ±1.01% (58 runs sampled)
While - yes x 16,742,721 ops/sec ±1.52% (56 runs sampled)
While - no x 8,866,357 ops/sec ±1.26% (56 runs sampled)
Fastest is While - yes,Node.contains - yes
﻿
### Safari 9

Node.contains - yes x 18,462,150 ops/sec ±8.08% (36 runs sampled)
Node.contains - no x 15,641,240 ops/sec ±11.13% (33 runs sampled)
While - yes x 7,399,323 ops/sec ±16.08% (28 runs sampled)
While - no x 5,136,469 ops/sec ±15.70% (29 runs sampled)
Fastest is Node.contains - yes

### Firefox 45

Node.contains - yes x 47,991,762 ops/sec ±5.60% (57 runs sampled)
Node.contains - no x 49,146,408 ops/sec ±0.86% (61 runs sampled)
While - yes x 18,736,808 ops/sec ±2.96% (60 runs sampled)
While - no x 5,482,678 ops/sec ±1.76% (59 runs sampled)
Fastest is Node.contains - no,Node.contains - yes
