# Spectra3D

Spectra3D is a 3D-only game engine project written in C++ with ImGui as the primary interface layer.<br />
This repository represents the foundation and long-term vision for a modern, modular, and high-performance engine focused on rendering, tooling, and extensibility.

> [!NOTE]
> This project is currently in the planning phase. Spectra3D is a long-term milestone and learning goal.<br />
> Development will evolve as C++ knowledge and engine design experience grow.

## Vision

Spectra3D aims to be:
- **3D-only**: Focused purely on 3D rendering, physics, and tooling.
- **Lightweight yet scalable**: Small, transparent core with room for advanced systems.
- **Developer-oriented**: Built to expose internals clearly for inspection, modification, and extension.
- **ImGui-integrated**: Using ImGui for editor panels, debugging, and in-engine tooling.

## Planned Features

- Core renderer built in modern C++
- ImGui-based editor UI for real-time manipulation and debugging
- Scene graph and entity-component-system (ECS) architecture
- Support for standard 3D asset formats (GLTF, OBJ, FBX)
- Material and shader management system
- Real-time lighting, shadows, and post-processing pipeline
- Physics integration (likely Bullet or PhysX in future iterations)
- Modular input, audio, and networking subsystems

## Goals for Early Development

- Establish a working build system with CMake.
- Create a minimal rendering window with ImGui overlay.
- Build small, incremental demos to validate each engine subsystem.

## Contributing

At this stage, Spectra3D is a personal milestone project.<br />
Contributions are welcome later once the project has a working foundation.<br />
Right now, discussions, advice, and architecture brainstorming are most useful.
