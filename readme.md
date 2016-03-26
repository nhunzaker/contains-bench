# While(node) vs Node.contains Benchmark

## Setup

Clone this repo and open index.html in any browser. Or visit
http://natehunzaker.com/contains-bench and do the same.

## Findings

### Chrome 49

```
Node.contains - yes x 16,561,750 ops/sec ±1.44% (59 runs sampled)
Node.contains - no x 15,785,211 ops/sec ±1.01% (58 runs sampled)
While - yes x 16,742,721 ops/sec ±1.52% (56 runs sampled)
While - no x 8,866,357 ops/sec ±1.26% (56 runs sampled)
Fastest is While - yes,Node.contains - yes
```

### Safari 9

```
Node.contains - yes x 18,462,150 ops/sec ±8.08% (36 runs sampled)
Node.contains - no x 15,641,240 ops/sec ±11.13% (33 runs sampled)
While - yes x 7,399,323 ops/sec ±16.08% (28 runs sampled)
While - no x 5,136,469 ops/sec ±15.70% (29 runs sampled)
Fastest is Node.contains - yes
```

### Firefox 45

```
Node.contains - yes x 47,991,762 ops/sec ±5.60% (57 runs sampled)
Node.contains - no x 49,146,408 ops/sec ±0.86% (61 runs sampled)
While - yes x 18,736,808 ops/sec ±2.96% (60 runs sampled)
While - no x 5,482,678 ops/sec ±1.76% (59 runs sampled)
Fastest is Node.contains - no,Node.contains - yes
```

### IE11

```
Node.contains - yes x 584,516 ops/sec ±5.45% (31 runs sampled)
Node.contains - no x 550,082 ops/sec ±7.57% (33 runs sampled)
While - yes x 450,457 ops/sec ±7.68% (32 runs sampled)
While - no x 254,522 ops/sec ±6.65% (33 runs sampled)
Fastest is Node.contains - yes,Node.contains - no
```

### IE10

```
Node.contains - yes x 1,246,569 ops/sec ±3.47% (55 runs sampled)
Node.contains - no x 1,181,269 ops/sec ±7.01% (54 runs sampled)
While - yes x 1,249,868 ops/sec ±4.47% (57 runs sampled)
While - no x 404,518 ops/sec ±1.29% (63 runs sampled)
Fastest is Node.contains - yes,While - yes,Node.contains - no
```

### IE9

```
Running benchmarks. Please wait...
Node.contains - yes x 1,406,193 ops/sec ±5.26% (49 runs sampled)
Node.contains - no x 1,372,341 ops/sec ±3.83% (49 runs sampled)
While - yes x 724,485 ops/sec ±5.64% (48 runs sampled)
While - no x 243,562 ops/sec ±4.96% (50 runs sampled)
Fastest is Node.contains - yes,Node.contains - no
```
