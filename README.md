# svg-preview.yazi

## Installation

ya pack -a michaelrommel/svg-preview

## Configuration

```
[plugin]
prepend_preloaders = [
    { mime = "image/svg+xml", run = "svg-preview" }
]
prepend_previewers = [
    { mime = "image/svg+xml", run = "svg-preview" },
]
```
