<p align="center">
  <img src="assets/header.svg" alt="From real-time 3D to interactive worlds" width="100%" />
</p>

# Fei Kang · 康飞

**Interactive World Models · Unreal Engine · Real-Time Systems**

[Google Scholar](https://scholar.google.com/citations?user=jJwVbnAAAAAJ) &nbsp; / &nbsp; [Research](#selected-research) &nbsp; / &nbsp; [Engineering](#engineering--open-source)

I work at the intersection of **real-time 3D systems and interactive world models**, with a background in Unreal Engine engineering. I am a co-author of **Matrix-Game 1.0, 2.0, 3.0, and 3.5**, a series exploring action-controllable generation, real-time interaction, and long-horizon consistency.

My interests center on connecting game environments with generative models: controllable simulation, synthetic data, spatial memory, and responsive interactive systems.

## Selected Research

### [Matrix-Game 3.5](https://matrix-game-v3-5.github.io/) · 2026

**Geometry-aware memory for persistent interactive worlds.**

Co-author. The project combines patch memory and camera conditioning with a static–dynamic world representation and progressive real-time distillation, targeting scene recall, camera control, and subject consistency over long sequences.

[Paper](https://arxiv.org/abs/2608.29910) · [Code](https://github.com/Riemann-Dynamics/Matrix-Game-3.5) · [Project](https://matrix-game-v3-5.github.io/)

### [Matrix-Game 3.0](https://matrix-game-v3.github.io/) · 2026

**Real-time streaming generation with long-horizon memory.**

Co-author. The 5B model achieves **up to 40 FPS at 720p**, with memory consistency over minute-long sequences. The system brings together a scalable data engine, camera-aware memory, and few-step autoregressive generation.

[Paper](https://arxiv.org/abs/2604.08995) · [Code](https://github.com/SkyworkAI/Matrix-Game/tree/main/Matrix-Game-3) · [Models](https://huggingface.co/Skywork/Matrix-Game-3.0) · [Project](https://matrix-game-v3.github.io/)

### Earlier Work

| Project | Research focus | Links |
| :--- | :--- | :--- |
| **Matrix-Game 2.0** · 2025 | Co-author. Few-step autoregressive diffusion for real-time, action-conditioned video generation at **25 FPS**. | [Paper](https://arxiv.org/abs/2508.13009) · [Code](https://github.com/SkyworkAI/Matrix-Game/tree/main/Matrix-Game-2) |
| **Matrix-Game** · 2025 | Co-author. A **17B** interactive world foundation model for controllable Minecraft generation, with the GameWorld Score benchmark. | [Paper](https://arxiv.org/abs/2506.18701) · [Code](https://github.com/SkyworkAI/Matrix-Game/tree/main/Matrix-Game-1) |

<sub>Performance figures describe the respective research systems under their reported evaluation settings; see the linked papers for details.</sub>

## Engineering & Open Source

### [Tencent / UnLua](https://github.com/Tencent/UnLua)

**C++ contribution to Unreal Engine 5 compatibility.**

Fixed incorrect vector math in the Lua bindings by replacing hard-coded `float` traits with the engine-compatible `unluaReal` type across vector, quaternion, and transform math traits. The fix was merged upstream.

[Merged PR #339](https://github.com/Tencent/UnLua/pull/339) · [Code change](https://github.com/Tencent/UnLua/pull/339/files)

### [PuertsStart](https://github.com/kf953741/PuertsStart)

**A minimal Unreal Engine 5.5 + TypeScript starter.**

A focused Puerts template with TypeScript runtime startup in `GameInstance`, TypeScript-to-JavaScript build configuration, and VS Code breakpoint debugging configuration.

[Repository](https://github.com/kf953741/PuertsStart)

---

**Research interests:** interactive world models · controllable simulation · long-horizon memory · synthetic data  
**Engineering foundation:** Unreal Engine · C++ · Lua integration · TypeScript tooling
