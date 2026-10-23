# Alejandro Figueroa

Software engineer working across production web infrastructure, native applications, GPU computing, computer vision, and simulation.

My production work at my day job includes analytics over 200M+ rows and authentication shared across five services. Independently, I build native Windows software, rendering and physics systems, perception pipelines, and developer tools.

## Selected work

- [**Falling Dice + Nonlinear Metamaterial Compression**](https://github.com/cybrdelic/falling-dice) — C++20 rigid-body simulation and CPU path tracing alongside a nonlinear beam-lattice solver with plasticity, damage, contact, validation, and STL export.
- [**IRIS Ω**](https://github.com/cybrdelic/iris-omega) — converts monocular machine video into a metric articulated world model while keeping measured geometry, appearance support, completion priors, and unknown space separate.
- [**Filelight Explorer**](https://github.com/cybrdelic/filelight-explorer) — native Windows file explorer written in C with a custom UI surface, deep file previews, and D3D11 GLB inspection.
- [**Twin Engine**](https://github.com/cybrdelic/twin-engine) — computational hardware and digital-twin work spanning drones, mechatronics, dynamics, validation, deterministic geometry, and offline rendering.

## Graphics, simulation and robotics

<a href="https://github.com/cybrdelic/cybr-iris09"><img src="https://raw.githubusercontent.com/cybrdelic/cybr-iris09/6aac71594c211cc5934674b2113d9db8c5ec17c6/media/iris-09.gif" width="400" alt="IRIS-09 optical mechanism from the recovered historical film"></a>
<a href="https://github.com/cybrdelic/cybr-cloud-fire-shaders"><img src="https://raw.githubusercontent.com/cybrdelic/cybr-cloud-fire-shaders/a3f165f2bfe1eb36ea62ca445b460cd057dfa227/media/cinematic-cloud.gif" width="400" alt="Procedural V17 cloud flight from the included historical film"></a>

These are excerpts from included historical films. The projects also retain source, setup instructions, engineering reports and bounded execution tests.

| Project | What is implemented and verified |
| --- | --- |
| [IRIS-09](https://github.com/cybrdelic/cybr-iris09/pull/1) | Procedural optical mechanism; native OpenGL still rendering and a localhost time/orbit/zoom preview. Windows execution and Linux/macOS Mesa rendering have independent numerical and changed-frame checks. Browser GPU Live has no verified frames on the tested paths; Film playback and native preview are separate. |
| [Cloud & Fire Shaders](https://github.com/cybrdelic/cybr-cloud-fire-shaders/pull/1) | Procedural cloud-flight shaders, offline rendering tools and a separate small-grid pressure-fireball study. Hosted macOS passes; the published Windows/Linux checks fail during viewer startup. A locally verified fix awaits publication and hosted validation. Cloud fields are not an atmospheric solver. |
| [Spawn locomotion lab](https://github.com/cybrdelic/spawn-locomotion-lab/pull/1) | Runnable Rapier contact experiments with three-OS mechanics/browser checks. Separate MuJoCo feedback-controller source still needs external checkpoints/assets; its walking candidate is unaccepted. |
| [Native WATER](https://github.com/cybrdelic/cybr-water-native/pull/1) | Three preserved water engines compile, simulate, reconstruct surfaces and render on Windows, Linux and macOS. Includes serial execution and precision/restoration checks; bounded tests do not establish complete-film or physical accuracy. |
| [Native FIRE](https://github.com/cybrdelic/cybr-fire-native/pull/1) | Native fire computation, checkpoints and rendering. Three-OS core tests and real Linux/macOS ARM64 Mesa simulation/rendering pass. Mesa uses CPU software rendering; Apple's OpenGL 4.1 cannot run this compute engine directly. |
| [ARX-6 belt](https://github.com/cybrdelic/cybr-arx6-belt/pull/1) | Procedural CAD, contact dynamics and actual browser frames pass on Windows, Linux and macOS. 166,026 exact table-access checks retain geometry and numerical data. Known power-loss overload remains. This is the pinned P5 baseline, not the latest ARX revision. |
| [ARX-6 compact](https://github.com/cybrdelic/cybr-arx6-compact/pull/1) | A distinct compact P5 drive architecture. Three-OS CAD/contact, native numerical tests and CPU rendering pass, with OpenMP or genuine serial execution. No manufacturing or hardware qualification. |
| [Shader portfolio](https://github.com/cybrdelic/cybr-shader-portfolio/pull/1) | Instrument Rebuild's mesh/raster exhibits and preserved earlier shader history. Cache restoration, native bakers, geometry and browser rendering pass across three OSes. This does not qualify newer Causal Bench work. |
| [HUMAN](https://github.com/cybrdelic/cybr-human/pull/10) | Tissue/contact research and continuous-face source. Three-OS synthetic mechanics, compiled native pixels and real media encoding pass. Anatomy data is absent, so this is not a complete face animation. |
| [Rainforest studies](https://github.com/cybrdelic/cybr-rainforest/pull/1) | Procedural botanical construction and recovery tools. Three-OS runtime/EXR checks pass; actual Blender Cycles rendering is verified on Windows. The latest full forest scene is not included. |
| [Current web portfolio](https://github.com/cybrdelic/cybr-portfolio/pull/13) | The October 22 seven-chapter snapshot passes 118 CPU tests and 18 Chrome walkthrough checks on Windows, Linux and macOS, including touch layouts and actual GPU-completion checks. Startup can be slow; two excluded rock maps remain disclosed. |

<a href="https://github.com/cybrdelic/spawn-locomotion-lab"><img src="https://raw.githubusercontent.com/cybrdelic/spawn-locomotion-lab/78d7a482fd6ea13933c67e19dcb5559ff8ff3bd8/docs/media/contact-lab-3d.png" width="640" alt="Earlier Rapier contact baseline with a procedural mannequin and force controls"></a>

*Earlier Rapier contact baseline; this image does not demonstrate accepted MuJoCo walking.*

[CYBR GEO draft PR 24](https://github.com/cybrdelic/cybr-geo/pull/24), pinned at `1c216fd`, provides a shared native engineering pipeline. Its default CAD, contact simulation, export/readback and PBR rendering passed Windows x64, Ubuntu x64 and macOS ARM64 CI. Nominal transfer passes while the matched friction-loss intervention fails. Continuous full-envelope clearance, production tolerances, belt pretension and hardware qualification remain unresolved; live Studio UI is uninspected.

The project links above point to reviewed changes, mostly in **unmerged draft PRs**. They do not imply those changes are on each default branch. Exact commits, executed checks, screenshots and remaining failures belong to the linked PR evidence. Hosted software rendering and emulated touch layouts do not establish physical-phone or universal GPU support. IRIS native previews are interactive stills, around 8–12 seconds per request on the tested Windows setup.

[Separate ARX source PR 2](https://github.com/cybrdelic/cybr-arx6-compact/pull/2), source commit `85bd6d2`, has been merged and contains Refined/P6B source and partial P6A evidence. P6A implementation remains missing. P6B's test articles and covers are not a complete printed arm; its newer load audit does not establish capacity. These sources have not received the pinned P5 execution checks above.

Newer WATER V6 and Causal Bench/Manufactured revisions need separate validation. Owner reports describe WATER V6 optical/reconstruction changes using earlier simulation state, FIRE checkpoint-view changes adding no physics or video, and Manufactured's reduced experiments with partly static lighting. Later Rainforest repair stills and realism findings are also owner-reported, separate from the tested source. Elemental Vortex source remains unavailable.

I work primarily in C, C++, TypeScript, Python, Rust, and GPU APIs including D3D11, CUDA, and WebGPU.

[Email](mailto:cybrvybe@gmail.com) · [Portfolio](https://cybrdelic.github.io) · [PyPI](https://pypi.org/user/cybrvybe/)
