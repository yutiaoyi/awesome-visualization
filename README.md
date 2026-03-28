## Awesome Visualization

An awesome-style curated list for **Visualization / Visual Analytics / Scientific Visualization / Data Visualization**.
Focus: **recent papers**, **classic works**, **datasets/benchmarks**, and **tools/systems**.

> References (format inspiration):
>
> - Video Generation: `[AlonzoLeeeooo/awesome-video-generation](https://github.com/AlonzoLeeeooo/awesome-video-generation)`
> - 3D Gaussian Splatting: `[MrNeRF/awesome-3D-gaussian-splatting](https://mrnerf.github.io/awesome-3D-gaussian-splatting/)`
> - Relighting: `[tandaily/Awesome-Relighting](https://github.com/tandaily/Awesome-Relighting)`
> - Sketch: `[MarkMoHR/Awesome-Sketch-Based-Applications](https://github.com/MarkMoHR/Awesome-Sketch-Based-Applications)`
> - Text-to-Image: `[Yutong-Zhou-cv/Awesome-Text-to-Image](https://github.com/Yutong-Zhou-cv/Awesome-Text-to-Image)`

---

## Table of Contents

- [Changelog](#changelog)
- [Contributing](#contributing)
- [Entry format](#entry-format)
- [Topic overview](#topic-overview)
- [Selected surveys / tutorials](#selected-surveys--tutorials)
- [Papers (by topic)](#papers-by-topic)
  - [Foundations & design](#foundations--design)
  - [Visual analytics & interaction](#visual-analytics--interaction)
  - [Explainability & model visualization](#explainability--model-visualization)
  - [Graph / network visualization](#graph--network-visualization)
  - [Time series & event sequence visualization](#time-series--event-sequence-visualization)
  - [High-dimensional visualization & DR](#high-dimensional-visualization--dr)
  - [Uncertainty visualization](#uncertainty-visualization)
  - [Scientific visualization (SciVis)](#scientific-visualization-scivis)
  - [Geo & spatiotemporal visualization](#geo--spatiotemporal-visualization)
  - [Text / multimodal visualization](#text--multimodal-visualization)
  - [Evaluation & reproducibility](#evaluation--reproducibility)
- [Datasets & benchmark suites](#datasets--benchmark-suites)
- [Tools / systems / open-source](#tools--systems--open-source)
- [Courses / books / blogs](#courses--books--blogs)
- [Related awesome lists](#related-awesome-lists)
- [License](#license)

---

## Changelog

- **2026-03-28**: add Distributed Neural Representation for Reactive In Situ Visualization (arXiv:2304.10516) under Scientific visualization (SciVis).
- **2026-03-28**: density-plot illumination (arXiv:2507.17265): main entry under Scientific visualization (SciVis), cross-ref from Foundations & design.
- **2026-03-28**: add SceneLoom (arXiv:2507.16466) under Foundations & design.
- **2026-03-28**: add data storytelling reflection survey (arXiv:2503.02631) under Selected surveys / tutorials.
- **2026-03-28**: add CD-TVD (arXiv:2508.08173) under Scientific visualization (SciVis).
- **2026-03-28**: add Sel3DCraft (arXiv:2508.00428) under Visual analytics & interaction.
- **2026-03-28**: add SEG-RobustEye (2025, VIS; IEEE 11298845) under Explainability & model visualization.
- **2026-03-28**: add VolSegGS (arXiv:2507.12667) under Scientific visualization (SciVis); restore concise VolMoVis row.
- **2026-03-28**: add Visualizationary (arXiv:2409.13109) under Text / multimodal visualization.
- **2026-03-28**: add Embodied NLI / speech patterns in immersive analytics (arXiv:2510.12156) under Visual analytics & interaction.
- **2026-03-28**: add RmdnCache (2024, TVCG; NSF PAR 10539350) under Scientific visualization (SciVis); restore concise VolMoVis row.
- **2026-03-28**: add Anisotropic Neural Representation (arXiv:2311.18311, TVCG 2025) under Scientific visualization (SciVis); restore concise VolMoVis row.
- **2026-03-28**: add DataWink (arXiv:2507.17734) under Text / multimodal visualization.
- **2026-03-28**: add MAICO (2025, TVCG; IEEE 10878127) under Visual analytics & interaction.
- **2026-03-28**: add GVVST (2024, TVCG; IEEE 10734252) under Graph / network visualization.
- **2026-03-28**: add GSCache (arXiv:2507.19718) under Scientific visualization (SciVis); restore concise VolMoVis row.
- **2026-03-28**: add VolumeSTCube (2025, TVCG; arXiv:2507.09917) under Geo & spatiotemporal visualization.
- **2026-03-28**: add VolMoVis (2026, IEEE) and DCINR (2025, TVCG) under Scientific visualization (SciVis); restore concise VolMoVis “My take” after accidental paste.
- **2026-03-26**: initialize repository scaffold.

---

## Contributing

PRs and issues are welcome. Please read `[CONTRIBUTING.md](./CONTRIBUTING.md)` first.

You can also open an issue to:

- **Add a paper/resource**: title + links (paper/project/code).
- **Fix metadata**: authors/venue/year/links/category.
- **Propose categories**: when a section grows large.

---

## Entry format

Use a **single table row** as the canonical format (consistent with all sections below):


| Year | Venue | Title       | Paper           | Project           | Code           | Tags       | My take      |
| ---- | ----- | ----------- | --------------- | ----------------- | -------------- | ---------- | ------------ |
| 2025 | VIS   | Paper title | [[Paper]](link) | [[Project]](link) | [[Code]](link) | tag1, tag2 | (your notes) |


Conventions:

- **Paper**: prefer official PDF / arXiv / publisher.
- **Code**: prefer official repo; mark reproductions clearly if needed.
- **Project**: homepage / demo / video.
- **Tags**: short and searchable (2–5 tags).

Cross-referencing the same paper across multiple sections (recommended):

- Put the **full row once** (the “main entry”) and add an anchor right above it: `<a id="paper-id"></a>`
- In other sections, add a lightweight row pointing to it: `[See main entry](#paper-id)`
- Suggested `paper-id` format: `venue-year-firstauthor-keyword` (e.g., `vis-2025-smith-chartqa`).

---

## Topic overview

> Start by adding entries by topic. When a section grows, split by year or move to dedicated pages.

- **Foundations & design**: perception, visual encoding, storytelling, grammars.
- **Visual analytics & interaction**: interaction paradigms, workflows, systems, user studies.
- **Explainability & model visualization**: XAI, model diagnosis/debugging.
- **Graph & network**: layouts, dynamic graphs, attributed graphs, analysis.
- **Time**: time series, event sequences, alignment, clustering.
- **High-dimensional & embeddings**: DR, projections, representation learning.
- **Uncertainty**: uncertainty encoding/propagation, decision support.
- **Scientific visualization (SciVis)**: volume rendering, flow, medical, simulation.
- **Geo & spatiotemporal**: maps, trajectories, spatial stats.
- **Text / multimodal**: document collections, chart understanding, VLM/LLM for vis.
- **Evaluation**: metrics, benchmarks, reproducibility, methodology.

---

## Selected surveys / tutorials

> Add must-read surveys/tutorials here; split later if needed.


| Year | Venue           | Title | Paper           | Project           | Code           | Tags             | My take      |
| ---- | --------------- | ----- | --------------- | ----------------- | -------------- | ---------------- | ------------ |
| 2025 | arXiv | Reflection on Data Storytelling Tools in the Generative AI Era from the Human-AI Collaboration Perspective | [[Paper]](https://arxiv.org/pdf/2503.02631) | - | - | survey, storytelling, generative-ai, human-ai-collaboration, llm, text-to-image | 在生成式 AI（**LLM / 文生图**等）公开约两年后，用专门的人机协作框架**对比最新与早期**数据叙事工具中的协作模式：既有长期常见的 **人主创 + AI 辅助**，也出现 **AI 主创 + 人审核** 等新形态；讨论收益、协作含义并提**未来方向**（非实现型工具论文，属领域反思与展望）。 |
| 20XX | Survey/Tutorial | Title | [[Paper]](link) | [[Project]](link) | [[Code]](link) | survey, tutorial | (your notes) |


---

## Papers (by topic)

### Foundations & design


| Year | Venue | Title | Paper           | Project           | Code           | Tags                       | My take      |
| ---- | ----- | ----- | --------------- | ----------------- | -------------- | -------------------------- | ------------ |
| 2025 | arXiv | SceneLoom: Communicating Data with Scene Context | [[Paper]](https://arxiv.org/pdf/2507.16466) | - | - | storytelling, data-journalism, data-video, vlm, multimodal, narrative, design, coordination | **SceneLoom**：面向数据新闻 / 数据视频等**数据叙事**场景，用 **VLM** 协调**图表**与**真实场景影像**，使二者在叙事上对齐而非割裂；形成性研究界定可视化—场景在**视觉对齐与语义一致**上的协调关系设计空间；系统抽取图像与图表特征，经推理完成空间组织、形状相似、布局一致、语义绑定等**设计映射**，生成多种**图像驱动**备选，支持浏览选择、交互微调与动画过渡；用户研究与案例库验证创意激发与表达外化。 |
| 2025 | arXiv | Visualization-Driven Illumination for Density Plots *(cross-ref)* | [See main entry](#arxiv-2025-chen-density-illumination) | - | - | density-plot, perception, storytelling-adjacent | 主条目在 SciVis：2D 密度聚合与感知编码；与经典 3D 体 SciVis 不同，但常用于大规模点样本探索。 |
| 20XX | Venue | Title | [[Paper]](link) | [[Project]](link) | [[Code]](link) | theory, perception, design | (your notes) |


### Visual analytics & interaction


| Year | Venue | Title                                                                                                       | Paper                                       | Project           | Code                                                    | Tags                                                                           | My take                                                                            |
| ---- | ----- | ----------------------------------------------------------------------------------------------------------- | ------------------------------------------- | ----------------- | ------------------------------------------------------- | ------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------- |
| 2025 | VIS | A Spatial Hybrid System for Visual Sensemaking (PC+VR)                                                      | [[Paper]](https://arxiv.org/pdf/2502.00853) | -                 | -                                                       | immersive-analytics, vr, hybrid-ui, visual-sensemaking, interaction, node-link | 提出 PC+VR 空间混合分析系统：在不显著增加切换开销的前提下结合 PC 的精确操作与 VR 的大空间导航，用户研究显示其体验优于 VR-only 且性能不下降。 |
| 2025 | VIS | A Multimodal Framework for Understanding Collaborative Design Processes                                     | [[Paper]](https://arxiv.org/pdf/2508.06117) | -                 | [[Code]](https://github.com/UniStuttgart-VISUS/reCAPit) | design-study, collaboration, multimodal, eye-tracking, visual-analytics, llm   | 多模态记录（音视频/笔记/眼动等）+ AI 提取 + 交互式可视分析，用于复盘与理解协作式设计工作坊中的决策过程与产出。                       |
| 2025 | VIS | <a id="arxiv-2025-biswas-vizgenie"></a>VizGenie: Toward Self-Refining, Domain-Aware Workflows for Next-Generation Scientific Visualization | [[Paper]](https://arxiv.org/pdf/2507.21124) | -                 | -                                                       | visual-analytics, agents, llm, scivis, hpc, volumetric, vqa, rag, code-generation, provenance | 面向 HPC 体数据的智能体式科学可视化：在预置过滤/切片/统计等工具之外，用 LLM 按需生成 VTK Python 等脚本并经后端自动验证后无缝集成，形成可持续扩展的能力库；自然语言特征查询配合微调视觉模型、图像 VQA、RAG 与交互溯源，把「显示颅骨/标出组织边界」类口语意图落到可复现脚本与迭代探索上，减轻大规模体数据反复调参的认知负担。 |
| 2025 | VIS   | Coordinated 2D-3D Visualization of Volumetric Medical Data in XR with Multimodal Interactions *(cross-ref)* | [See main entry](#vis-2025-liu-xr-medvis)   | -                 | -                                                       | xr, immersive, interaction, user-study                                         | -                                                                                  |
| 2025 | TVCG | MAICO: A Visualization Design Study on AI-Assisted Music Composition                                       | [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10878127) | [[Project]](https://visvar.github.io/pub/rau2025maico.html) | [[Code]](https://github.com/visvar/MAICoV2) | design-study, visual-analytics, music, generative-ai, human-ai-collaboration, parameter-space, symbolic-music | **MAICO**：面向 **AI 辅助符号音乐创作**的可视分析界面与人机共创流程；用**参数空间/度量与相似性布局**并行呈现来自多模型的大量短样本，支持生成、浏览、对比、筛选与编辑。论文以**约 5 个月**与职业作曲家长期合作为设计研究主线，并用于威尼斯双年展相关创作实践；含可复现印章与开源实现。 |
| 2025 | arXiv | Embodied Natural Language Interaction (NLI): Speech Input Patterns in Immersive Analytics                  | [[Paper]](https://arxiv.org/pdf/2510.12156) | -                 | -                                                       | visual-analytics, immersive-analytics, natural-language, speech, user-study, wizard-of-oz, embodiment, xr | **沉浸式分析中的语音 NLI**：**N=15**、**Wizard of Oz**，从 **734** 条话语得到 **1280** 条 speech acts 并做轴向编码，结合**语义熵**度量输入不确定性；归纳 **五种**语音输入模式（具身与非具身表述随分析任务、阶段及具身线索依赖而动态混合），并对照用户反思讨论语音交互难点与**设计启示**。 |
| 2025 | arXiv | Sel3DCraft: Interactive Visual Prompts for User-Friendly Text-to-3D Generation                            | [[Paper]](https://arxiv.org/pdf/2508.00428) | -                 | -                                                       | visual-analytics, text-to-3d, mllm, visual-prompt, generative-ai, interaction, hci, multimodal | **Sel3DCraft**：面向 **Text-to-3D** 的**视觉提示工程**系统，把「盲试提示」变成**有引导的可视化流程**：**双分支**（检索 + 生成）探索多样 3D 候选；**多视角混合评分**用 **MLLM** 与高阶指标评估多视角一致性与 3D 质量；**提示驱动的可视分析**套件支持缺陷识别与迭代 refinement；测试与用户研究表明较既有 T23D 工作流更利于**设计者**发挥创意。 |
| 20XX | Venue | Title                                                                                                       | [[Paper]](link)                             | [[Project]](link) | [[Code]](link)                                          | interaction, visual-analytics, system                                          | (your notes)                                                                       |


### Explainability & model visualization


| Year | Venue | Title | Paper           | Project           | Code           | Tags                                | My take      |
| ---- | ----- | ----- | --------------- | ----------------- | -------------- | ----------------------------------- | ------------ |
| 2025 | VIS | SEG-RobustEye: Understanding Medical Image Segmentation Models | [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11298845) | - | - | explainability, visual-analytics, medical-imaging, segmentation, robustness, xai, endoscopy | **SEG-RobustEye**：在 **ProactiV** 框架上面向**医学分割**（尤其**内镜**）定制可视分析，用于在**真实输入变换**下理解**鲁棒性**与模型行为；支持**全局 / 实例 / 子群**多层分析，子群级模式用于**发现规律**与**泛化性**评估；与深度学习开发者做案例验证。 |
| 20XX | Venue | Title | [[Paper]](link) | [[Project]](link) | [[Code]](link) | explainability, model-understanding | (your notes) |


### Graph / network visualization


| Year | Venue | Title | Paper           | Project           | Code           | Tags           | My take      |
| ---- | ----- | ----- | --------------- | ----------------- | -------------- | -------------- | ------------ |
| 2024 | TVCG | GVVST: Image-Driven Style Extraction From Graph Visualizations for Visual Style Transfer | [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10734252) | - | - | graph, network, style-transfer, image-driven, layout, color, deep-learning | **GVVST** 从参考**图可视化图像**中自动抽取风格并迁移到新拓扑：将风格拆为**全局**（布局、配色）与**局部**（结点/边的填充、线型、尺寸等）；全局侧用显著性/区域划分与聚类推断布局与主色，局部侧用深度网络做多标签属性分类与几何回归；配套用户研究验证较基线更接近参考风格、减少手工重设计成本。 |
| 20XX | Venue | Title | [[Paper]](link) | [[Project]](link) | [[Code]](link) | graph, network | (your notes) |


### Time series & event sequence visualization


| Year | Venue | Title | Paper           | Project           | Code           | Tags                        | My take      |
| ---- | ----- | ----- | --------------- | ----------------- | -------------- | --------------------------- | ------------ |
| 20XX | Venue | Title | [[Paper]](link) | [[Project]](link) | [[Code]](link) | time-series, event-sequence | (your notes) |


### High-dimensional visualization & DR


| Year | Venue | Title                                     | Paper                                       | Project           | Code           | Tags                                                          | My take                              |
| ---- | ----- | ----------------------------------------- | ------------------------------------------- | ----------------- | -------------- | ------------------------------------------------------------- | ------------------------------------ |
| 2025 | VIS   | Dataset-Adaptive Dimensionality Reduction | [[Paper]](https://arxiv.org/pdf/2507.11984) | -                 | -              | dimensionality-reduction, optimization, hyperparameter-tuning | 用数据结构复杂度来指导 DR 方法/超参选择，并支持早停以减少试错成本。 |
| 20XX | Venue | Title                                     | [[Paper]](link)                             | [[Project]](link) | [[Code]](link) | dimensionality-reduction, embedding                           | (your notes)                         |


### Uncertainty visualization


| Year | Venue | Title | Paper           | Project           | Code           | Tags        | My take      |
| ---- | ----- | ----- | --------------- | ----------------- | -------------- | ----------- | ------------ |
| 20XX | Venue | Title | [[Paper]](link) | [[Project]](link) | [[Code]](link) | uncertainty | (your notes) |


### Scientific visualization (SciVis)


| Year | Venue | Title                                                                                                                                   | Paper                                                                  | Project                                    | Code                                             | Tags                                                                                             | My take                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| ---- | ----- | --------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------- | ------------------------------------------ | ------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 2024 | TVCG | RmdnCache: Dual-Space Prefetching Neural Network for Large-Scale Volume Visualization                                                  | [[Paper]](https://par.nsf.gov/servlets/purl/10539350)                  | -                                          | -                                                | scivis, volume-rendering, large-scale, prefetching, neural-network, io, interactive              | **RmdnCache**：面向**大规模体可视化**的 I/O 瓶颈，在**原始体数据空间**与**神经压缩表示空间**上做**双空间预取**神经网络，预测访问并提前加载以降低交互式体渲染等待；IEEE TVCG 2024（DOI 10.1109/TVCG.2024.3410091），上栏链接为 NSF PAR 录用稿全文。                                                                                                                                                                                                                                                                                                                                 |
| 2023 | arXiv | Distributed Neural Representation for Reactive in situ Visualization                                                                    | [[Paper]](https://arxiv.org/pdf/2304.10516)                            | -                                          | -                                                | scivis, in-situ, distributed, inr, compression, hpc, ascent, reactive, large-scale-volume          | **分布式体 INR** 面向 **in situ 可视化**：训练/推理组织使进程间**无需交换体素数据**，在压缩速度、质量与压缩比上达到较强表现；并支持高时间频率下大规模模拟数据的**缓存**策略，便于 **reactive in situ**；与 **Ascent** 集成，在真实科学模拟上评估性能与可用性。 |
| 2025 | arXiv | <a id="arxiv-2025-chen-density-illumination"></a>Visualization-Driven Illumination for Density Plots | [[Paper]](https://arxiv.org/pdf/2507.17265) | - | - | scivis, density-plot, scatterplot, illumination, perception, large-data, aggregation | **可视化驱动光照**用于**密度图**（大规模离散点**聚合**视图，缓解散点过绘）：强调**中高密区**结构与**低密区**离群点可读性，并用**图像合成**减轻光照与**密度色标**相互干扰；定量 + 受控实验与多数据集（可达约 **200 万**点）。**可重点关注**：与经典 3D 体/流场 SciVis 不同，属 2D 聚合与感知编码，但在**海量科学点样本 / 投影后探索**中很常见。 |
| 2025 | VIS   | Natural Language-Driven Viewpoint Navigation for Volume Exploration via Semantic Block Representation                                   | [[Paper]](https://arxiv.org/pdf/2508.06823)                            | -                                          | -                                                | scivis, volume-rendering, viewpoint-navigation, natural-language, clip, reinforcement-learning   | 这篇工作把“看体数据找视角”变成自然语言驱动任务：先对体数据做语义块表示，再用微调 CLIP 对齐图像-文本语义，最后用强化学习按文本意图搜索最匹配视角。核心洞察是把 reward 从整图相似度细化到语义块级反馈，可显著提升目标结构定位与导航可解释性，降低非专家进行 3D 探索的门槛。                                                                                                                                                                                                                                                                                                                                                                                     |
| 2025 | VIS   | NLI4VolVis: Natural Language Interaction for Volume Visualization                                                                       | [[Paper]](https://arxiv.org/pdf/2507.12621)                            | [[Project]](https://nli4volvis.github.io/) | -                                                | scivis, volume-rendering, natural-language, open-vocabulary, 3dgs, interactive-editing           | 用自然语言把体可视化中的“查询-编辑-风格化”统一起来：基于可编辑 3DGS + 开放词汇感知 + 多智能体协同，实现非专家也能实时进行语义级体数据探索。 系统采用的核心技术：1. 多智能体 VPA 循环：利用多个 LLM 智能体通过“感知-决策-行动”循环解析用户意图并自动调用可视化工具 。2. 可编辑 3D 高斯泼溅 (iVR-GS)：基于 3DGS 扩展了法线、环境光、漫反射等属性，并支持通过连接高斯参数实现多场景合成与独立编辑 。3. 熵导向视图选择与 CLIP 嵌入：通过计算 alpha 通道的图像熵筛选信息量最大的视角，结合 CLIP 模型实现跨模态的“开放词汇”对象查询 。4. 2D 扩散模型风格化：集成 InstructPix2Pix (IP2P) 技术，允许用户通过文字指令为科学可视化结果添加艺术风格 。                                                                                                                                                     |
| 2025 | arXiv | <a id="arxiv-2025-tang-texgs-volvis"></a>TexGS-VolVis: Expressive Scene Editing for Volume Visualization via Textured Gaussian Splatting | [[Paper]](https://arxiv.org/pdf/2507.13586)                            | -                                          | -                                                | scivis, volume-rendering, 3dgs, gaussian-splatting, npr, stylization, text-driven, image-driven, differentiable-rendering | 面向体可视化非真实感（NPR）表达：用可微 **2D 高斯** 表示 VolVis 场景，并为每个高斯增加纹理与着色属性以解耦几何与外观，缓解传统 3DGS 强耦合导致的风格化发糊；结合预训练大模型支持**任意风格**迁移与实时渲染；再配图像/文本驱动的 NPR 场景编辑与 2D-lift-3D 分割，实现局部、可控的细粒度编辑。与「手写规则、单风格」类 NPR 相比，强调效率、观感与编辑灵活度。                                                                                                                                                                                                                                                                                                                                                           |
| 2025 | arXiv | VolSegGS: Segmentation and Tracking in Dynamic Volumetric Scenes via Deformable 3D Gaussians                                              | [[Paper]](https://arxiv.org/pdf/2507.12667)                            | -                                          | -                                                | scivis, volume-rendering, 3dgs, gaussian-splatting, segmentation, tracking, time-varying, deformable, interactive | **VolSegGS**：用**可变形 3D 高斯**表示动态体场景并做**实时**新视角合成；交互**分割**——粗分用高斯**视图无关颜色**，细分用**亲和场网络**；将分割嵌入高斯，借助变形在时间上**连续跟踪**区域；面向大规模**时变模拟/体数据**在低算力下的**探索式**可视化与分析（相对仅追求重建质量的视图合成方法，强调分割/跟踪与交互）。                                                                                                                                                                                                                                                                                                                                 |
| 2025 | VIS | GSCache: Real-Time Radiance Caching for Volume Path Tracing using 3D Gaussian Splatting                                                   | [[Paper]](https://arxiv.org/pdf/2507.19718)                            | -                                          | -                                                | scivis, volume-rendering, path-tracing, radiance-caching, 3dgs, monte-carlo, photorealistic        | **GSCache**：将 **3D 高斯泼溅**改作**路径空间**多级辐射缓存，可在渲染过程中**在线训练**并随光照、传输函数等变化自适应；挂接到体路径追踪后，在**计算量可比**的前提下降低 MC 方差、提升体科学可视化画质；相对均匀采样+NEE 基线与神经辐射缓存 SOTA 有定量/定性对比。                                                                                                                                                                                                                                                                                                                                 |
| 2025 | VIS | VizGenie: Self-Refining Workflows for Scientific Visualization *(cross-ref)*                                                          | [See main entry](#arxiv-2025-biswas-vizgenie)                          | -                                          | -                                                | scivis, agents, llm, hpc, volumetric, natural-language                                           | -                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| 2025 | VIS   | Coordinated 2D-3D Visualization of Volumetric Medical Data in XR with Multimodal Interactions                                           | [[Paper]](https://arxiv.org/abs/2506.22926)                            | -                                          | -                                                | scivis, medical, volume, xr, immersive, multimodal                                               | 做了一个XR 医学可视化系统，输入 CT/MRI 体数据，输出2D 切片与 3D 网格模型联动显示，并支持手势 + LLM 语音交互，大幅提升医学影像理解效率 This paper developed an XR medical visualization system that takes CT/MRI volume data as input and provides coordinated display of 2D slices and 3D mesh models. It supports gesture and LLM-based voice interaction, significantly improving the efficiency of medical image understanding.                                                                                                                                                        |
| 2025 |VIS | NeRF-CA: Dynamic Reconstruction of X-ray Coronary Angiography from Sparse-views                                                         | [[Paper]](https://arxiv.org/pdf/2408.16355)                            | -                                          | [[Code]](https://github.com/kirstenmaas/NeRF-CA) | scivis, medical, 4d-reconstruction, nerf, sparse-view, motion                                    | 用 NeRF 做冠脉造影（X-ray CA）的 4D 重建：针对极少视角 + 心脏运动，把场景拆成“运动的血管+静态背景”，在仅 4 张造影视图的临床稀疏设置下仍能得到可用的动态重建，并开源代码。                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| 2025 | TVCG | Anisotropic Neural Representation Learning for High-Quality Neural Rendering                                                            | [[Paper]](https://arxiv.org/pdf/2311.18311)                            | -                                          | -                                                | scivis, neural-rendering, nerf, implicit-representation, spherical-harmonics, view-dependent     | 针对标准 NeRF 体渲染沿射线离散积分时**忽略段内方向信息**、易产生模糊与歧义的问题，提出**各向异性神经表示**：用 **球谐（SH）引导**的 MLP 表达视角相关各向异性特征以消歧并保持效率；并对各向异性能量做**正则**以防过拟合；可作为插件接入多种 NeRF 变体，在合成与真实场景上提升新视角合成质量（arXiv 2023，期刊版 TVCG 2025）。                                                                                                                                                                                                                                                                                                                              |
| 2025 | VIS   | MoE-INR: Implicit Neural Representation with Mixture-of-Experts for Time-Varying Volumetric Data Compression                            | [[Paper]](https://academicweb.nd.edu/~cwang11/papers/vis25-moeinr.pdf) | -                                          | -                                                | scivis, compression, inr, moe, time-varying-volume                                               | 提出 MoE-INR，把时空体数据压缩建模拆成 policy network + shared encoder + 多个 expert decoders，自动进行规则/非规则分区并由专家解码，减少边界伪影并提升高压缩比下的重建质量；在多个数据集上相对传统压缩与现有 INR 取得更优 PSNR/LPIPS/CD。                                                                                                                                                                                                                                                                                                                                                                        |
| 2025 | TVCG  | DCINR: A Divide-and-Conquer Implicit Neural Representation for Compressing Time-Varying Volumetric Data in Hours.                         | [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10976573) | -                                          | -                                                | scivis, compression, inr, time-varying-volume, divide-and-conquer, entropy, clustering, model-parallelism | 分治 INR 缓解单体网络压缩时变科学数据时训练动辄数天、架构“一刀切”与多 GPU 梯度同步通信瓶颈：4D 体划为非重叠时空块 → 聚类选代表性块去冗余 → 按块**时空熵**分配网络容量（高熵大区、低熵小区）→ 每块独立微型 INR（PE + 编解码 + Adam/MSE），训练期**模型并行、块间无通信**，论文报告相对中心化 INR 约 **10–50×** 加速，将优化压到**小时级**；解压按坐标取块、载权重后缝合。相较 4D 网格+线性插值类加速，把时间并入分块坐标建模，减轻 4D 插值噪声，利于极高压缩比下仍保持较高 PSNR。 |
| 2025 | VIS | <a id="arxiv-2025-sun-f-hash"></a>F-Hash: Feature-Based Hash Design for Time-Varying Volume Visualization via Multi-Resolution Tesseract Encoding | [[Paper]](https://arxiv.org/pdf/2507.03836)                            | -                                          | -                                                | scivis, inr, time-varying-volume, hash-encoding, 4d, neural-rendering, feature-tracking, ray-marching | 把时变体 INR 的瓶颈放在「输入编码」上：F-Hash 用多分辨率 4D Tesseract 嵌入网格 + 多级无碰撞哈希映射，在紧凑参数下提高动态时空哈希容量、减少桶浪费，显著加快大规模时变体数据上的 INR 训练收敛；编码与具体特征检测算法解耦，可统一服务特征追踪与演化可视化；另提出自适应光线步进以加速时变神经体的渲染采样。                                                                                                                                                                                                                                                                                                                                                           |
| 2025 | VIS   | FLINT: Learning-based Flow Estimation and Temporal Interpolation for Scientific Ensemble Visualization                                  | [[Paper]](https://arxiv.org/abs/2409.19178)                            | -                                          | [[Code]](https://github.com/HamidGadirov/FLINT)  | scivis, ensemble, flow-estimation, temporal-interpolation, time-varying                          | 用深度学习同时做科学 ensemble 数据的流场估计与时间插值；即使缺失或完全没有 GT flow，也能通过模块化 loss 在监督/无监督场景下工作，并为每个 timestep 生成对应 flow，提升时变标量场的连续可视化与分析。FLINT 利用深度学习，从时序科学数据中估计出描述流体运动的流场，并实现平滑的时间插值，主要用于科学可视化、流场分析、数据补全和流畅动画生成。                                                                                                                                                                                                                                                                                                                                      |
| 2025 | arXiv | CD-TVD: Contrastive Diffusion for 3D Super-Resolution with Scarce High-Resolution Time-Varying Data                                  | [[Paper]](https://arxiv.org/pdf/2508.08173)                            | -                                          | [[Code]](https://github.com/Xin-Gao-private/CD-TVD) | scivis, time-varying-volume, super-resolution, diffusion, contrastive-learning, simulation, fluid, atmospheric | **CD-TVD**：大规模科学模拟中 **高分辨率时变体数据昂贵/稀缺** 时的 **3D 超分**——**对比学习编码器**与**改进的扩散超分**在历史模拟上预训练，学习 LR/HR 退化与细节；微调阶段仅用 **一个**新产生的 HR 时间步 + 带**局部注意力**的扩散模块，降低对海量 HR 训练样本的依赖；在**流体与大气**模拟数据上验证，强调资源高效的体数据增强与后续分析/可视化链路。 |
| 2025 | VIS | <a id="arxiv-2025-zhang-flow-llm-semantic-alignment"></a>Automatic Semantic Alignment of Flow Pattern Representations for Exploration with Large Language Models | [[Paper]](https://arxiv.org/pdf/2508.06300)                            | -                                          | -                                                | scivis, flow, streamlines, llm, natural-language, semantic-alignment, cross-modal              | 把流线段变成距离矩阵后经去噪自编码器得到紧凑流型表示，再用投影层对齐到 LLM 文本嵌入，配合 GPT-4o 自动生成的指令数据与跨模态注意力做文本—流型匹配，无需手工标注流型–语义对应即可用自然语言检索并可视化流线结构；面向探索式流可视化的「流数据表示 + 多模态语义对齐」管线。                                                                                                                                                                                                                                                                                                                                                                                                    |
| 2025 | VIS | MC-INR: Efficient Encoding of Multivariate Scientific Simulation Data using Meta-Learning and Clustered Implicit Neural Representations | [[Paper]](https://arxiv.org/pdf/2507.02494)                            | -                                          | -                                                | scivis, multivariate, inr, meta-learning, clustering, unstructured-grid, Neural Data Compression | 提出了一种名为 MC-INR 的神经编码框架，主要用于高效压缩和表示非结构化网格上的多变量科学模拟数据 。该模型以时空坐标 (x, y, z, t) 作为输入 ，通过 k-means 聚类将复杂的空间域划分为多个局部区域，并结合元学习技术实现对局部结构的快速适应 。在网络架构上，它采用了带有分支层的 $CoordNet_B$，为每个物理变量（如温度、压力等）分配独立的神经分支 ，最终输出该坐标点对应的多个物理变量预测值 。实验证明，该方法在保持高重建精度的同时，显著降低了海量科学数据的存储开销 。 请简单、精简地总这篇论文提出的 Branched CoordNet 架构通过以下流程处理数据：输入与编码：将原始的时空坐标 $(x, y, z, t)$ 输入模型，通过位置编码 (PE) 转化为高维特征向量 。全局提取 (GFE)：由全局特征提取器接收编码特征，负责捕捉数据中通用的整体结构模式 。局部提取 (LFE)：将 GFE 的输出分发至 M 个独立的分支，每个分支针对一个特定的物理变量（如温度或压力）学习其精细的局部特征 。最终输出：模型最终输出一组向量，其中每个分量对应一个特定物理变量的预测值 。 |
| 2026 | IEEE | VolMoVis: Continuous Implicit Neural Representation for Real-Time Dynamic Cone-Beam CT Reconstruction | [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11261850) | - | - | scivis, medical, 4d-cbct, inr, hexplane, deformation-field, igrt | 针对 4D CBCT 等动态断层成像：用 INR 将动态体拆为静态参考与呼吸相位驱动的 3D 位移场，Hexplane 特征 + 轻量 MLP 实现近实时推理；可在任意相位连续合成体积，参考体上标注的分割可经变形场推广到全部相位；报告较 FDK/SART 更高的 PSNR/SSIM、A100 上 256³ 约 29.5 ms、肿瘤中心误差约 <0.41 mm，面向 IGRT 等呼吸运动监控。 |
| 20XX | Venue | Title                                                                                                                                   | [[Paper]](link)                                                        | [[Project]](link)                          | [[Code]](link)                                   | scivis, volume-rendering, flow                                                                   | (your notes)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |


### Geo & spatiotemporal visualization


| Year | Venue | Title                                                                                | Paper                                       | Project           | Code           | Tags                                             | My take                                                                                                                                                                                                                                                                                                                                                                    |
| ---- | ----- | ------------------------------------------------------------------------------------ | ------------------------------------------- | ----------------- | -------------- | ------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 2026 | VIS | Data-Driven Compute Overlays for Interactive Geographic Simulation and Visualization | [[Paper]](https://arxiv.org/pdf/2506.23364) | -                 | -              | geovis, simulation, webgpu, overlay, interactive | 用 WebGPU 把“地理仿真→可视化 overlay 生成”做成可交互 GPU compute workflow（几毫秒到秒级），适合在 web/native 3D 地图中即时调参并查看结果。 当前 VIS 领域不再局限于传统图形编码与交互设计，将 “物理仿真 / 并行计算 + 实时可视化 + 交互式探索” 整合为端到端可用系统，并在性能、部署与用户体验上形成突破，已成为主流且受认可的贡献形式；同时，WebGPU 等 Web 端 GPU 计算技术正成为可视化的重要基础设施，推动学科边界从单纯渲染展示向可交互、轻量化、高性能的计算可视化扩展，即使主题偏向仿真，只要围绕 “如何让用户更高效、直观地理解数据” 展开，就符合 VIS 的核心价值，也为入门者提供了明确路径 —— 把系统工程与性能优化转化为可视化的真实价值。 |
| 2025 | TVCG | Volume-Based Space-Time Cube for Large-Scale Continuous Spatial Time Series           | [[Paper]](https://arxiv.org/pdf/2507.09917) | -                 | -              | geovis, spatiotemporal, space-time-cube, volume-rendering, spatial-time-series, interaction | **VolumeSTCube**：将离散分布的空间时间序列按时空立方体思路转为**连续体**，再辅以**体绘制**缓解遮挡、**表面绘制**强化图案与光照细节，并设计时空/时空联合交互支撑探索；针对大规模 STC 的遮挡与深度歧义，论文通过计算实验、专家案例与 12 名非专家用户研究相对既有基线展示优势。 |
| 20XX | Venue | Title                                                                                | [[Paper]](link)                             | [[Project]](link) | [[Code]](link) | geo, spatiotemporal                              | (your notes)                                                                                                                                                                                                                                                                                                                                                               |


### Text / multimodal visualization

> Visualization × NLP/MLLM/Multimodal (e.g., chart understanding, data-centric QA, structured extraction, LLM-assisted VA).






| Year | Venue | Title                                                                                                       | Paper                                       | Project           | Code                                                                       | Tags                                                       | My take                                                                                                  |
| ---- | ----- | ----------------------------------------------------------------------------------------------------------- | ------------------------------------------- | ----------------- | -------------------------------------------------------------------------- | ---------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| 2025 | TVCG  | HINTs: Sensemaking on Large Collections of Documents with Hypergraph Visualization and INTelligent Agents   | [[Paper]](https://arxiv.org/pdf/2403.02752) | -                 | -                                                                          | text-vis, sensemaking, hypergraph, llm, agents             | 用超图+层级聚类来组织大规模语料，并把 LLM 作为“数据准备/标注/提示驱动”的智能代理嵌入交互流程，支持主题结构与关键词双线索的 corpus sensemaking。                   |
| 2025 | arXiv | DataWink: Reusing and Adapting SVG-based Visualization Examples with Large Multimodal Models                 | [[Paper]](https://arxiv.org/pdf/2507.17734) | -                 | -                                                                          | text-vis, mllm, svg, example-driven, authoring, conversational-agent, multimodal | **DataWink**：面向「范例驱动」制图——用 **LMM** 从高质量 **SVG 可视化范例**中解析数据编码，并以中间表示衔接原始 SVG 与可执行可视化程序；用户通过**对话代理**描述改编意图，并用**按需生成控件**同时改数据映射与视觉样式，在尽量保留范例美感的前提下完成个性化创作；**N=12** 用户研究（复现 + 自由探索）评估易学性与有效性。 |
| 2024 | arXiv | Visualizationary: Automating Design Feedback for Visualization Designers using LLMs                         | [[Paper]](https://arxiv.org/pdf/2409.13109) | [[Project]](https://osf.io/v7hu8) | -                                                                          | text-vis, llm, design-feedback, authoring, perception, user-study, longitudinal, chatgpt | **Visualizationary**：用现成 **LLM（ChatGPT）** 为可视化设计者提供**可操作的定制反馈**；系统由**可视化设计准则 preamble** + 从图表图像提取显著指标的**感知过滤器**组成；**N=13**（6 新手 / 4 中级 / 3 专家）**多日纵向**从零创作，表明自然语言指导对**资深设计者**亦有 refinement 帮助；补充材料见 OSF。 |
| 2025 | VIS   | Probing the Visualization Literacy of VLMs with AG-CAM                                                      | [[Paper]](https://arxiv.org/pdf/2504.05445) | -                 | [[Code]](https://osf.io/fp3rg/?view_only=9b11aaec4ddf4656b205ebc53f4ef9db) | chart, vlm, visualization-literacy, explainability, ag-cam | 用 attention+gradient 的 AG-CAM 让图表 QA 的 VLM “显性化”它在看哪些 token/patch，不只评估对错，也分析内部推理与关注区域，利于更透明、可复现的可视化素养研究。 |
| 2025 | VIS   | Coordinated 2D-3D Visualization of Volumetric Medical Data in XR with Multimodal Interactions *(cross-ref)* | [See main entry](#vis-2025-liu-xr-medvis)   | -                 | -                                                                          | xr, multimodal, llm, voice, medical                        | -                                                                                                        |
| 2025 | VIS   | SimVecVis: A Dataset for Enhancing MLLMs in Visualization Understanding *(cross-ref)*                       | [See main entry](#simvecvis)                | -                 | -                                                                          | chart, mllm, vis-understanding                             | -                                                                                                        |
| 2025 | VIS | Automatic Semantic Alignment of Flow Pattern Representations for Exploration with LLMs *(cross-ref)*        | [See main entry](#arxiv-2025-zhang-flow-llm-semantic-alignment) | -                 | -                                                                          | flow, llm, multimodal, natural-language                    | -                                                                                                        |
| 2025 | VIS | VizGenie: Self-Refining, Domain-Aware SciVis Workflows *(cross-ref)*                                          | [See main entry](#arxiv-2025-biswas-vizgenie)                   | -                 | -                                                                          | agents, llm, vqa, rag, scivis                              | -                                                                                                        |
| 2025 | arXiv | TexGS-VolVis: Textured Gaussian Splatting for Volume NPR *(cross-ref)*                                        | [See main entry](#arxiv-2025-tang-texgs-volvis)                 | -                 | -                                                                          | volume, 3dgs, stylization, multimodal                      | -                                                                                                        |
| 20XX | Venue | Title                                                                                                       | [[Paper]](link)                             | [[Project]](link) | [[Code]](link)                                                             | tag1, tag2                                                 | (your notes)                                                                                             |


### Evaluation & reproducibility

> Methodology papers: how to evaluate, user study methods, metrics, reproductions, diagnostics.
> Reusable datasets and benchmark suites should go to the section below.


| Year | Venue | Title                                                                                 | Paper                                                | Project           | Code           | Tags                            | My take      |
| ---- | ----- | ------------------------------------------------------------------------------------- | ---------------------------------------------------- | ----------------- | -------------- | ------------------------------- | ------------ |
| 2025 | VIS | Probing the Visualization Literacy of VLMs with AG-CAM *(cross-ref)*                  | [See main entry](#arxiv-2025-vlm-vis-literacy-agcam) | -                 | -              | evaluation, explainability, vlm | -            |
| 2025 | VIS   | SimVecVis: A Dataset for Enhancing MLLMs in Visualization Understanding *(cross-ref)* | [See main entry](#simvecvis)                         | -                 | -              | dataset, benchmark, evaluation  | -            |
| 20XX | Venue | Title                                                                                 | [[Paper]](link)                                      | [[Project]](link) | [[Code]](link) | evaluation, reproducibility     | (your notes) |


---

## Datasets & benchmark suites

> Reusable **datasets** and **benchmark suites** (ideally: data + tasks/protocols + metrics + code).
> Evaluation methodology / reproducibility papers should go to the section above.

### 2025


| Year | Venue | Title                                                                   | Paper                                       | Project                                    | Code                                            | Tags                                                                  | My take                                                                                                                                                                                                                                                                                                                                                                                                    |
| ---- | ----- | ----------------------------------------------------------------------- | ------------------------------------------- | ------------------------------------------ | ----------------------------------------------- | --------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 2025 | VIS   | SimVecVis: A Dataset for Enhancing MLLMs in Visualization Understanding | [[Paper]](https://arxiv.org/abs/2506.21319) | -                                          | [[Code]](https://github.com/VIDA-Lab/SimVecVis) | dataset, chart, mllm, vis-understanding, Visualization with/for/in AI | 解决“多模态大模型看不懂图表”的问题，方法是设计一种简化的图表结构表示 SimVec，并配套构建数据集 SimVecVis 来训练模型，从而提升图表问答和可视化理解能力。 This work addresses the problem that multimodal large language models struggle to understand charts by introducing a simplified structured representation, SimVec, and constructing a corresponding dataset, SimVecVis, to train models, thereby improving chart question answering and visualization understanding. |
| 2025 | VIS   | VISANATOMY: An SVG Chart Corpus with Fine-Grained Semantic Labels       | [[Paper]](https://arxiv.org/pdf/2410.12268) | [[Project]](https://VisAnatomy.github.io/) | -                                               | dataset, chart, svg, semantic-labeling, corpus                        | 提出一个高质量 SVG 图表语料库 VISANATOMY（942 张图、40 类图表、38 万+细粒度语义标注），把“图表类型”之外的元素角色、层级分组、布局与视觉编码系统化标注出来，可直接支撑图表语义解析、分解、分类与无障碍导航等任务，是图表理解方向的重要基础数据资源。                                                                                                                                                                                                                                                                   |


### Other years (placeholder)


| Year | Venue | Title | Paper           | Project           | Code           | Tags       | My take      |
| ---- | ----- | ----- | --------------- | ----------------- | -------------- | ---------- | ------------ |
| 20XX | Venue | Title | [[Paper]](link) | [[Project]](link) | [[Code]](link) | tag1, tag2 | (your notes) |


---

## Tools / systems / open-source

> Research systems (paper+code) and practical toolchains (rendering, web vis, interaction frameworks).


| Name | Type             | Link           | Description          | Tags | My take      |
| ---- | ---------------- | -------------- | -------------------- | ---- | ------------ |
| Name | Repo/Tool/System | [[Link]](link) | One-line description | tool | (your notes) |


---

## Courses / books / blogs

### Courses


| Name        | Link           | Notes | My take      |
| ----------- | -------------- | ----- | ------------ |
| Course Name | [[Link]](link) | -     | (your notes) |


### Books


| Year | Title     | Link           | Notes | My take      |
| ---- | --------- | -------------- | ----- | ------------ |
| 20XX | Book Name | [[Link]](link) | -     | (your notes) |


### Blogs / Tutorials


| Title | Link           | Notes | My take      |
| ----- | -------------- | ----- | ------------ |
| Title | [[Link]](link) | -     | (your notes) |


---

## Related awesome lists

> Add more related awesome/survey repositories here.

- `[AlonzoLeeeooo/awesome-video-generation](https://github.com/AlonzoLeeeooo/awesome-video-generation)`
- `[tandaily/Awesome-Relighting](https://github.com/tandaily/Awesome-Relighting)`
- `[MarkMoHR/Awesome-Sketch-Based-Applications](https://github.com/MarkMoHR/Awesome-Sketch-Based-Applications)`
- `[Yutong-Zhou-cv/Awesome-Text-to-Image](https://github.com/Yutong-Zhou-cv/Awesome-Text-to-Image)`

---

## License

TBD (MIT is a common choice for awesome lists).