# edvance-assets

**Static 3D models and an image for the EdVance AR project, kept in one place so they can be loaded by URL.**

![glTF](https://img.shields.io/badge/glTF-GLB-87C540?style=flat-square)
![Assets only](https://img.shields.io/badge/content-assets%20only-555555?style=flat-square)

## Overview

This repository holds files, not code. Each EdVance AR experience is set up with the URL of a GLB/GLTF model or an image, and this repository stores such files so they can be linked directly. The binaries are committed straight to Git (no Git LFS).

## Contents

| File | Type | Size | Description |
|---|---|---|---|
| `assets/models/tree.glb` | glTF binary | 14.1 MB | Tree model |
| `assets/models/blasrs.glb` | glTF binary | 5.6 MB | 3D model |
| `assets/models/retro_computer_setup_free.glb` | glTF binary | 2.5 MB | Retro computer setup model |
| `assets/models/toy.jpeg` | JPEG image | 96 KB | Photo of a toy dollhouse |

## Usage

Reference a file through its raw GitHub URL:

```
https://raw.githubusercontent.com/4waiz/edvance-assets/main/assets/models/tree.glb
```

GitHub serves these URLs with `Access-Control-Allow-Origin: *`, so browser-based 3D and AR viewers on other domains can fetch them.

## Notes

The repository does not record where the models come from or under which licence they were published (`retro_computer_setup_free.glb`, for example, looks like a downloaded free model). Check the original source before reusing them elsewhere.

---

Built by [Awaiz Ahmed](https://github.com/4waiz).
