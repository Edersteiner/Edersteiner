# Gabriel Eder

Engine, tools and systems programmer from Sweden, currently studying at Futuregames Stockholm.

I specialise in engine, tools and systems programming, with a strong interest in rendering and in scripting integration. Most of what I do lives in C++, Vulkan, Slang and AngelScript, with Unreal Engine, Godot and Unity on the game side.

**Portfolio:** [gabrieleder.com](https://www.gabrieleder.com) · **LinkedIn:** [gabriel-eder](https://www.linkedin.com/in/gabriel-eder-278a1b381/) · **Email:** gabriel.eder@me.com

## Projects

### [Gibbon Engine](https://www.gabrieleder.com/projects/gibbon)

A Vulkan game engine and editor written from scratch in C++20 (2026, ongoing).

- Vulkan 1.3 renderer: render graph, bindless resources, GPU-culled indirect draws, clustered lighting
- Dynamic global illumination from ray-traced probes (DDGI) and denoised ray-traced reflections
- AngelScript gameplay scripting on the stock compiler, with generated typed bindings, hot reload and script properties in the editor
- Reflection code generator: one annotation gives serialization, inspector UI and script bindings
- Full editor: docking UI framework, scene composer, undoable inspector, content browser, play-in-editor

Source is private for now; I'm happy to walk through it on request.

### [Fate](https://www.gabrieleder.com/projects/fate)

Co-op FPS with roguelike and hero shooter elements, built by a team of ten in a fork of Unreal Engine 5 (2026).

- Networked first and third person animation for three heroes on a shared rig
- Rain and wet-surface rendering, including a Lumen shading model fix in engine source
- Game-feel components for viewmodels and camera modifiers, DLSS research and integration spec

### [Frogga](https://www.gabrieleder.com/projects/frogga)

A vertical slice of a physics-based Metroidvania in Godot 4 and C#, made with one artist (2025). Won Audience Choice and Game of the Year at Make A Game.

- Active-ragdoll animation system driven by Hooke's law on top of Jolt Physics
- Behaviour tree plugin so enemies could be built in the editor without code
- General-purpose save system that persists physics state across zone loads

## Open source on this account

- [Lizaveta](https://github.com/Edersteiner/Lizaveta): graphical X11 file manager with Vim bindings, written in C
- [zed-editor-for-unity](https://github.com/Edersteiner/zed-editor-for-unity): Zed as Unity's external script editor, with Windows support
- [CPP-Game-Laboratory](https://github.com/Edersteiner/CPP-Game-Laboratory): a collection of games and game logic in C++
- [CrossCompilerScript](https://github.com/Edersteiner/CrossCompilerScript): builds a GCC and Binutils cross toolchain for hobby OS development
- AI coursework in C#: [behaviour trees](https://github.com/Edersteiner/gabriel_eder_ai_lab_4_behaviour_trees), [GOAP](https://github.com/Edersteiner/gabriel-eder-ai-lab-5-goap), [steering](https://github.com/Edersteiner/gabriel_eder_ai_lab_3_steering), [A*](https://github.com/Edersteiner/gabriel_eder_ai_lab_2_astar)

## Skills

**Languages:** C++, C, C#, Rust, AngelScript, GDScript, TypeScript, Python
**Engines and tools:** Unreal Engine, Godot, Unity, RenderDoc, Nvidia Nsight, GDB and LLDB
**Graphics:** Vulkan, WebGPU (wgpu, Dawn), OpenGL, Slang, HLSL, GLSL, WGSL
