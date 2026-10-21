<p align="center">
  <img src="assets/header.svg" alt="World models and embodied intelligence" width="100%" />
</p>

# Fei Kang · 康飞

**AI Research & Engineering · [Skywork AI](https://github.com/SkyworkAI)**  
Former **3D Engine Technical Expert · [Tencent](https://github.com/Tencent)**  
World Models · Embodied Intelligence · World Action Models · Model Post-Training

[Google Scholar](https://scholar.google.com/citations?user=jJwVbnAAAAAJ&hl=en) &nbsp; / &nbsp; [Data Engine](#featured-contribution--world-model-data-engine) &nbsp; / &nbsp; [Research](#selected-research) &nbsp; / &nbsp; [Media](#media-coverage) &nbsp; / &nbsp; [Engineering](#engineering--open-source)

I work on **world models, embodied foundation models, and model post-training** at Skywork AI. My work spans interactive world generation, robot learning, and **World Action Models (WAMs)**, supported by a background in 3D engines and simulation.

I **pioneered and built the Unreal Engine-based data-generation pipeline introduced in Matrix-Game 2.0 (2025)**, connecting controllable 3D simulation with scalable world-model training. I am also a co-author of **Riemann-1.0, Matrix-3D, and the Matrix-Game series (1.0–3.5)**.

## Featured Contribution — World-Model Data Engine

**Pioneered the use of Unreal Engine to generate precisely synchronized action–video pairs for interactive world-model training**, designing and building the pipeline introduced in [Matrix-Game 2.0](https://arxiv.org/abs/2508.13009).

## Areas of Work

- **World models & WAMs** — Interactive generation, visual dynamics, action conditioning, and long-horizon consistency.
- **Embodied AI** — Robotic foundation models and the connection between world simulation and executable policies.
- **Model post-training** — Task adaptation and capability refinement for downstream use.
- **World-model data infrastructure** — Unreal Engine-based synthetic-data generation, controllable environments, and aligned training supervision.

## Selected Research

### [Riemann-1.0](https://riemann-dynamics.github.io/Riemann-1.0-Website/) · 2026

**An embodied World Action Model for Physical AI.**

Co-author. A causal autoregressive model that unifies **robot policy execution and action-conditioned world simulation**, learning from heterogeneous embodied experience. Reported success rates include **99.0% on LIBERO**, **94.3% on RoboTwin 2.0**, and **85.0% on evaluated long-horizon real-world manipulation tasks**.

[Paper](https://arxiv.org/abs/2608.27033) · [Project & Robot Demos](https://riemann-dynamics.github.io/Riemann-1.0-Website/)

### [Matrix-Game 3.5](https://matrix-game-v3-5.github.io/) · 2026

**Geometry-aware memory for persistent interactive worlds.**

Co-author. Combines patch memory and camera conditioning with a static–dynamic world representation and progressive distillation for long-horizon scene recall, camera control, and subject consistency.

[Paper](https://arxiv.org/abs/2608.29910) · [Code](https://github.com/Riemann-Dynamics/Matrix-Game-3.5) · [Project](https://matrix-game-v3-5.github.io/)

### [Matrix-Game 3.0](https://matrix-game-v3.github.io/) · 2026

**Real-time streaming generation with long-horizon memory.**

Co-author. The 5B model achieves **up to 40 FPS at 720p**, with memory consistency over minute-long sequences, combining a scalable data engine, camera-aware memory, and few-step autoregressive generation.

[Paper](https://arxiv.org/abs/2604.08995) · [Code](https://github.com/SkyworkAI/Matrix-Game/tree/main/Matrix-Game-3) · [Models](https://huggingface.co/Skywork/Matrix-Game-3.0) · [Project](https://matrix-game-v3.github.io/)

### [Matrix-3D](https://matrix-3d.github.io/) · 2025

**Omnidirectional, explorable 3D world generation.**

Co-author. Connects trajectory-guided panoramic video diffusion with 3D reconstruction to generate explorable worlds from text or an image. Introduces **Matrix-Pano**, a synthetic dataset of **116K panoramic video sequences** with depth and trajectory annotations.

[Paper](https://arxiv.org/abs/2508.08086) · [Code](https://github.com/SkyworkAI/Matrix-3D) · [Project](https://matrix-3d.github.io/)

### Earlier Work

| Project | Research focus | Links |
| :--- | :--- | :--- |
| **Matrix-Game 2.0** · 2025 | Co-author; designed and built the Unreal Engine data-generation pipeline. Real-time, action-conditioned video generation at **25 FPS**. | [Paper](https://arxiv.org/abs/2508.13009) · [Code](https://github.com/SkyworkAI/Matrix-Game/tree/main/Matrix-Game-2) |
| **Matrix-Game** · 2025 | Co-author. A **17B** interactive world foundation model for controllable Minecraft generation, with the GameWorld Score benchmark. | [Paper](https://arxiv.org/abs/2506.18701) · [Code](https://github.com/SkyworkAI/Matrix-Game/tree/main/Matrix-Game-1) |

<sub>Performance figures describe the respective research systems under their reported evaluation settings; see the linked papers for details.</sub>

## Media Coverage

### Riemann-1.0

- [证券时报 — 昆仑万维：2026年为“世界模型元年”，三款产品布局物理AI与具身智能](https://www.stcn.com/article/detail/4071208.html)
- [量子位 — 看了20万小时「人类干活实录」，机器人悟了](https://www.qbitai.com/2026/07/454592.html)

### Matrix-Game 3.5

- [证券时报 — 昆仑万维WAIC官宣“世界模型元年”：从生成内容到理解物理世界关键转折](https://www.stcn.com/article/detail/4028872.html)
- [雷锋网（新浪科技转载）— 世界模型迎来「中国引领时刻」，昆仑万维 Matrix-Game 3.5 要迈向真实世界](https://finance.sina.com.cn/tech/roll/2026-07-23/doc-iniiufvk4588289.shtml)

### Matrix-Game 3.0

- [新华网客户端 — 昆仑万维携AIGC全家桶亮相2026中关村论坛](https://app.xinhuanet.com/news/article.html?articleId=20260330b976208b7fc046ab8487932edbc7fa6c)
- [量子位 — 国产玩家亮剑世界模型！把全模态卷到顶后，天工AI不藏了](https://www.qbitai.com/2026/03/392835.html)

### Matrix-Game 2.0

- [证券时报 — 昆仑万维：正式发布并开源「Matrix-Game 2.0」模型](https://www.stcn.com/article/detail/3049494.html)
- [机器之心（新浪科技转载）— 开源版Genie 3世界模型来了：实时+长时间交互，单卡可跑，国内公司出品](https://finance.sina.com.cn/tech/2025-08-19/doc-infmntcm7796241.shtml)

### Matrix-3D

- [新智元（36氪刊载）— 李飞飞押注的「世界模型」，中国自研Matrix-3D已抢先实现了？](https://www.36kr.com/p/3419306619096455)
- [量子位 — 拿下3D生成行业新标杆！昆仑万维Matrix-3D新模型鲨疯了，一张图建模游戏场景](https://www.qbitai.com/2025/08/321401.html)

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

**Current focus:** world models · embodied AI · WAMs · model post-training  
**Engineering foundation:** 3D engines · Unreal Engine · C++ · simulation & synthetic data
