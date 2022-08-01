# Parallel graph coloring

This project is a comprehensive study for the graph coloring problems, where the most of the available algorithms in the literature have been implemented and expremented, and the results have been compared on different aspects, and final results are released that determine what are the most powerful algorithms in terms of memory consumption, time consumption, and colors consumptions. Also, the least powerful ones are determined. In this comparison, not only the literature algorithms are implemented and compared. However, two new algorithms are introduced.

This is a short "user's manual"; for information on the algorithms and the design choices refer to DOCUMENTATION.md.

## Compile (Linux)

This is a standard CMake project; just build it out-of-tree and compile it with `make`.

```
mkdir build
cd build
cmake ..
make
cd ..
```

## Run

```
build/graph_coloring [--csv] [--parse-only] path_to_graph
```

The flag `--csv` enables CSV output; `--parse-only` quits after the parsing stage.