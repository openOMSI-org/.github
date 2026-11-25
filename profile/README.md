# openOMSI.org

A from-scratch recreation of the bus simulator OMSI 2, written in Rust. It loads the existing
OMSI 2 maps, buses, scenery and mods as they are, and needs an installed copy of OMSI 2. This
is the only official openOMSI organization (previously `openOMSI-Project`).

[Website](https://openomsi.org/) | [Download](https://openomsi.org/download/) |
[Discord](https://discord.gg/openomsi)

## Install openOMSI

1. Install OMSI 2 (Steam or retail) with its stock content.
2. Download openOMSI from the [latest release](https://github.com/openOMSI-org/openOMSI/releases/latest) and install it.
3. Start the launcher, choose a map, line, tour and bus, and press **Start the duty**.

Details are in [Getting started](https://github.com/openOMSI-org/openOMSI/blob/main/docs/GETTING_STARTED.md).

## Projects

| Repository | Contents |
| --- | --- |
| [openOMSI](https://github.com/openOMSI-org/openOMSI) | the game and its launcher |
| [openMapper](https://github.com/openOMSI-org/openMapper) | a simple map editor: draw roads, place objects, shape the ground, drive the map in openOMSI |
| [openOMSI Plugins](https://github.com/openOMSI-org/openOMSI-Plugins) | the catalog of reviewed, open source Lua plugins |
| [Development Tools](https://github.com/openOMSI-org/openOMSI-Development-Tools) | the plugin workbench: projects, API docs, the `.oop` compiler, the Rust SDK |
| [mX](https://github.com/openOMSI-org/mX) | a bindless graphics library in Rust for Metal 3, Vulkan and Direct3D 12, with wgpu's API on top |

## Dependencies

| Repository | Contents |
| --- | --- |
| [wgpu-openomsi](https://github.com/openOMSI-org/wgpu-openomsi) | fork of wgpu |
| [gpu-allocator](https://github.com/openOMSI-org/gpu-allocator) | fork of the GPU memory allocator for Vulkan, DirectX 12 and Metal |
| [angle-openomsi](https://github.com/openOMSI-org/angle-openomsi) | pinned builds of Google ANGLE for the DirectX 11 option |
| [egui-openomsi](https://github.com/openOMSI-org/egui-openomsi) | fork of egui for the launcher and Development Tools |
| [tauri-openomsi](https://github.com/openOMSI-org/tauri-openomsi) | fork of Tauri |

## Contributing

Issues and pull requests are welcome, see
[CONTRIBUTING.md](https://github.com/openOMSI-org/openOMSI/blob/main/CONTRIBUTING.md). To build
from source, read [docs/BUILDING.md](https://github.com/openOMSI-org/openOMSI/blob/main/docs/BUILDING.md).

## Licence

Each repository has the licence its `LICENSE` file names. OMSI and OMSI 2 are trademarks of
their respective owners. openOMSI is an independent project and is not affiliated with them.
