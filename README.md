# Cheburashka
A Vertex Cover solver

## Build instructions

Nothing special for that, the project is sumply built with CMake.

```
$ cmake -DCMAKE_BUILD_TYPE="Release" .
$ make
```

## Usage

This solver is participating in PACE 2019, so the input and output formats are as described on the [https://pacechallenge.org/2019/vc/vc_format/](challenge website).

### Example:

```
$ ./cheburashka
c A complete graph of three vertices
p td 3 3
1 2
2 3
1 3
s vc 3 2
3
2
```

Everything before "s vc" is the input, everything after is the output.
