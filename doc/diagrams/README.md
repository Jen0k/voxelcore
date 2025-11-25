# Architecture diagrams

`architecture.dot` visualizes the high-level VoxelCore engine architecture. It focuses on the central engine runtime, frontend stack, content/asset pipeline, world lifecycle, and supporting services.

## Exporting

Render to PNG with Graphviz:

```sh
dot -Tpng architecture.dot -o architecture.png
```

Render to SVG (better for zooming without quality loss):

```sh
dot -Tsvg architecture.dot -o architecture.svg
```

Open the resulting file in any viewer or embed it into other documentation as needed.
