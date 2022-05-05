# three-d-io

**This is an attempt to do a general crate for loading, saving and editing 3D assets. The idea is that it should be possible to use it as a base for any type of visualization or advanced editing tools, a bit like the `image` crate, just for 3D assets. Contributions are very much appreciated!**

The crate contain a set of common assets that are useful when doing graphics which can be loaded using the `io` module or constructed manually.
When in memory, the assets can be for example be
- visualised, for example using the [three-d](https://github.com/asny/three-d) crate or in a CPU ray tracer
- imported into a rust-based game engine
- edited and saved again

### TriMesh (all features: `tri-mesh`)

TriMesh | Deserializing | Serializing | Feature| 
| ------------ | -------------| ------------- | ------------- |
OBJ | :heavy_check_mark: |  :white_large_square: | `obj` |
glTF | :heavy_check_mark: |  :white_large_square: | `gltf` |
USDZ | :white_large_square: |  :white_large_square: | |
STL | :white_large_square: |  :white_large_square: | |
FBX | :white_large_square: |  :white_large_square: | |

### Texture2D / TextureCube (all features: `texture2d`)

| Format | Deserializing | Serializing | Feature| 
| ------------ | ------------- | ------------- | ------------- |
| PNG | :heavy_check_mark: |  :heavy_check_mark: | `png` |
| JPEG | :heavy_check_mark: |  :heavy_check_mark: | `jpeg` |
| DDS | :heavy_check_mark: |  :heavy_check_mark: | `dds` |
| HDR | :heavy_check_mark: |  :white_large_square: | `hdr` |
| GIF | :heavy_check_mark: |  :heavy_check_mark: | |
| WebP | :heavy_check_mark: |  :heavy_check_mark: | |
| PNM | :heavy_check_mark: |  :heavy_check_mark: | |
| TIFF | :heavy_check_mark: |  :heavy_check_mark: | |
| BMP | :heavy_check_mark: |  :heavy_check_mark: | |
| ICO | :heavy_check_mark: |  :heavy_check_mark: | |
| farbfield | :heavy_check_mark: |  :heavy_check_mark: | |
