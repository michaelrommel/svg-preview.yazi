# inkscape-preview.yazi

## Installation

ya pack -a michaelrommel/inkscape-preview

## Configuration

```
[plugin]
prepend_preloaders = [
    { mime = "image/svg+xml", run = "inkscape-preview" }
]
prepend_previewers = [
    { mime = "image/vg+xml", run = "inkscape-preview" },
]
```
