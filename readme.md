# MapWeaver3D Windows Library Pack

This repository provides prebuilt third-party libraries needed to compile MapWeaver3D under Windows.

## Contents

| Library | Version | Description |
|---------|---------|-------------|
| OpenSceneGraph (OSG) | 3.5.6 | 3D rendering engine |
| Qt 5 | 5.12.10 | Cross-platform UI framework |
| GDAL | 3.12.4 | Geospatial data abstraction library |
| PROJ | 9.8.1 | Coordinate transformation library |
| OPENSSL | 3.6.2 | Open source SSL/TLS encryption library. |

## Usage

1. Download the latest library pack archive from this repository.
2. Extract it into the MapWeaver3D source tree at `<MapWeaver3D>`:

After extraction the directory will look like:
```
MapWeaver3D/
└── 3rdParty/
└── application/
├── CMakeModules/
├── core/
├── MapWeaver3D-LibPack-Windows/
└── plugins/
```

3. The MapWeaver3D CMake build system will locate the libraries automatically under `./MapWeaver3D-LibPack-Windows/`.

## Requirements

- Windows 10 or later (64-bit)
- Visual Studio 2022 or later (v143 toolset)
- CMake 3.10+

## Notes

- All binaries are built for the **x64** platform. Both Release and Debug configurations are provided where applicable.

## License

The libraries included in this pack are distributed under their respective open-source licenses. See each library's documentation for details.