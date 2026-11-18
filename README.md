# Awesome-3D-Generative-AI-Spatial-Modeling
# Awesome-3D-Generative-AI-Spatial-Modeling

# Top 3D Generative AI & Spatial Modeling Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Text-to-3D, Image-to-3D Diffusion, 3D-as-Code for LLMs, Spatial World Generation & Local Mesh Synthesis*  
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **3D Generative AI & Spatial Modeling**. These tools generate textured 3D meshes, PBR materials, quad-retopologized game assets, and explorable 3D spatial worlds directly from text prompts, reference images, or LLM-authored code.

**Examples** include Meshy.ai, Tripo 3D, Hyper3D Rodin, Spline AI, Luma Genie, CSM 3D, Sloyd.ai, Kaedim, Masterpiece X, 3DFY.ai, and Sandflow-ai/sand3d (the category leaders). 

**Open-source emphasis**: This section is heavily expanded with every major active project for local text/image-to-3D generation, 3D-as-code LLM modeling libraries, part-decomposed mesh synthesis, and ComfyUI/Blender AI pipelines — ideal for game developers, 3D artists, spatial AI researchers, and indie studios building local, credit-free 3D workflows.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Meshy.ai](https://www.meshy.ai/)**  
  All-in-one cloud AI 3D model generator offering text-to-3D, image-to-3D, AI PBR texturing, remeshing, and direct Blender, Unity, and Unreal Engine plugins.

- **[Tripo 3D](https://tripo3d.ai)**  
  High-speed generative 3D platform producing detailed meshes with full PBR materials, multi-view reconstruction, segmentation, and Smart Mesh topology optimization.

- **[Hyper3D Rodin (Deemos)](https://hyper3d.ai)**  
  High-fidelity generative 3D spatial modeling platform featuring multi-image geometry synthesis, OmniCraft mesh editing, and clean quad/triangle topology exports.

- **[Spline AI](https://spline.design/ai-generate)**  
  Cloud AI 3D generation and texture styling integrated directly inside the Spline collaborative web 3D editor for interactive WebGL scenes.

- **[Luma AI (Luma Genie)](https://lumalabs.ai)**  
  Fast cloud text-to-3D and image-to-3D generator delivering quad-retopologized meshes, PBR textures, and multi-format downloads (`GLB`, `FBX`, `OBJ`, `USDZ`).

- **[Common Sense Machines (CSM 3D)](https://csm.ai)**  
  Multimodal AI spatial modeling platform converting images, text, and video into game-ready 3D meshes and interactive spatial assets via web studio and API.

- **[Sloyd.ai](https://www.sloyd.ai/)**  
  Parametric and generative AI 3D asset platform tailored for game developers needing instant, clean, low-poly hard-surface props without manual retopology.

- **[Kaedim](https://kaedim3d.com)**  
  AI-powered 3D production pipeline combining machine learning with artist-in-the-loop quality control to convert 2D concept art into clean, UV-unwrapped game meshes.

- **[Masterpiece X](https://masterpiecex.com)**  
  Cloud text-to-3D generative platform built for creators and VR/XR workflows to generate, preview, and remix textured 3D objects in the browser.

- **[3DFY.ai](https://3dfy.ai)**  
  Scalable cloud generative 3D solution focused on automated, structured, high-quality 3D asset creation for e-commerce, gaming, and enterprise catalogs.


## Open-Source GitHub Projects

- **[Sandflow-ai/sand3d](https://github.com/Sandflow-ai/sand3d)**  
  Open-source (`Apache-2.0`) declarative Python 3D-as-code modeling library built over Blender's `bpy` specifically for LLMs, enabling deterministic part-by-part articulated 3D objects in a ~3,600-token API with `GLB`, `URDF`, `USD`, `OBJ`, and `STL` export, paired with the [Sand3D 100K Dataset](https://sandflow.ai/sand3d/) and [Sandflow/sand3d-automate](https://huggingface.co/datasets/Sandflow/sand3d-automate).

- **[Tencent Hunyuan3D-2 / 2.1](https://github.com)**  
  High-resolution open-source 3D asset generation suite combining flow-based shape diffusion (`Hunyuan3D-DiT`) and PBR texture synthesis (`Hunyuan3D-Paint`) with Blender and Gradio integration.

- **[Microsoft TRELLIS](https://github.com)**  
  Large-scale open-source (`MIT`) 3D generative foundation model utilizing Structured 3D Latents (SLAT) to synthesize textured meshes, 3D Gaussians, and radiance fields from text or images.

- **[TripoSR (VAST-AI-Research)](https://github.com)**  
  Fast feed-forward open-source (`MIT`) 3D reconstruction model developed with Stability AI that generates textured 3D meshes from a single image in under a second on GPU.

- **[InstantMesh (TencentARC)](https://github.com)**  
  Open-source (`Apache-2.0`) feed-forward framework combining multi-view diffusion and sparse-view Large Reconstruction Models (LRM) for rapid single-image-to-3D mesh generation.

- **[PartCrafter](https://github.com)**  
  Open-source structured 3D generative model capable of synthesizing compositional, part-decomposed 3D meshes from single RGB images rather than fused single-shell geometry.

- **[HunyuanWorld-1.0](https://github.com)**  
  Open-source generative 3D spatial world modeling framework designed to synthesize explorable, interactive 3D scenes from text prompts or reference images.

- **[OpenAI Shap-E](https://github.com)**  
  Official open-source (`MIT`) code and weights for generating conditional 3D implicit functions, textured meshes, and NeRFs directly from text or image prompts.

- **[threestudio](https://github.com)**  
  Unified open-source (`Apache-2.0`) PyTorch framework implementing leading text-to-3D, image-to-3D, and 3D-to-3D diffusion distillation pipelines (`DreamFusion`, `Magic3D`, `Zero123`, `ProlificDreamer`).

- **[Wonder3D](https://github.com)**  
  Open-source single-image-to-3D reconstruction framework leveraging cross-domain diffusion to generate consistent multi-view normal maps and detailed textured meshes.

- **[Phidias-Diffusion (3DTopia)](https://github.com)**  
  ICLR 2025 open-source (`MIT`) reference-augmented generative 3D diffusion model supporting text, image, and 3D structural conditioning.

- **[mymeshy](https://github.com)**  
  Local-first open-source AI 3D asset generator supporting text/image-to-3D, PBR texture baking, multi-format export, and an MCP server for AI coding agents on local GPUs.

- **[PolyzonMaker](https://github.com)**  
  Free, open-source cross-platform desktop app built with Tauri and Rust for turning text prompts or photos into print-ready `STL` and `3MF` 3D models locally.

- **[blendrelay-mcp](https://github.com)**  
  Open-source Blender AI add-on and Model Context Protocol (MCP) server enabling Claude Code, Codex, and AI agents to generate and edit 3D scenes, Geometry Nodes, and meshes via prompts.

- **[chisel (EYamanS/chisel)](https://github.com)**  
  Headless, GPU-free open-source MCP server allowing AI agents to procedurally construct, boolean-edit (CSG), render, and export `.glb`/`.obj` 3D models from primitives.

### Additional Strong Open-Source Options

- **[AIEXX_GENAI_IMAGE_TO_3D](https://github.com/AIExxplorer/AIEXX_GENAI_IMAGE_TO_3D)** and **[ComfyUI-3D-Pack](https://github.com)** for node-based ComfyUI workflows chaining `Zero123++`, `TripoSR`, `InstantMesh`, and `Hunyuan3D`.
- **[lightningpixel/modly](https://github.com)** for a cross-platform local desktop 3D `.glb` mesh generator powered by modular GitHub AI extensions.
- **[DreamCraft3D](https://github.com)** and **[CRM (Convolutional Reconstruction Model)](https://github.com)** for hierarchical 3D content synthesis and high-resolution UV-textured mesh reconstruction.
- **[4DNeX (3DTopia)](https://github.com)** and **[SyncDreamer](https://github.com)** for feed-forward 4D dynamic spatial modeling and multi-view consistent 3D generation.
- **[Best Open-Source Text-to-3D Tools Guide](https://biff.ai/best-open-source-text-to-3d-tools-on-github/)** and **[Objaverse-XL](https://github.com)** for comparative benchmarks and 10M+ 3D training objects.

**Frameworks for building custom systems**: Combine **Sandflow-ai/sand3d** (for deterministic LLM 3D-as-code) with **Hunyuan3D-2** or **Microsoft TRELLIS**, **ComfyUI-3D-Pack**, and **blendrelay-mcp** for end-to-end local 3D generative AI and spatial modeling pipelines.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Local 3D diffusion and reconstruction models (such as Hunyuan3D-2, TRELLIS, and InstantMesh) typically require a dedicated GPU with 8GB–24GB+ VRAM, whereas LLM 3D-as-code tools like **Sand3D** run on standard Blender Python environments.
- Verify model weight licenses (`MIT`, `Apache-2.0`, `CC-BY-4.0`, or non-commercial research terms) before using generated 3D assets in commercial games or products.

---

**Made for 3D artists, game developers, spatial AI engineers, and creative technologists.**  
Let's make 3D generative AI and spatial modeling more open, programmable, and accessible.
