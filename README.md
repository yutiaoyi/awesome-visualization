

## Awesome Visualization

一个关于**可视化（Visualization / Visual Analytics / Scientific Visualization / Data Visualization）的资源与论文综述式合集。重点关注近年论文脉络、经典工作、数据集/评测、开源项目与实践工具链**。

> 参考与致敬（格式与组织方式借鉴）：
>
> - Video Generation: `[AlonzoLeeeooo/awesome-video-generation](https://github.com/AlonzoLeeeooo/awesome-video-generation)`
> - 3D Gaussian Splatting: `[MrNeRF/awesome-3D-gaussian-splatting](https://mrnerf.github.io/awesome-3D-gaussian-splatting/)`
> - Relighting: `[tandaily/Awesome-Relighting](https://github.com/tandaily/Awesome-Relighting)`
> - Sketch: `[MarkMoHR/Awesome-Sketch-Based-Applications](https://github.com/MarkMoHR/Awesome-Sketch-Based-Applications)`
> - Text-to-Image: `[Yutong-Zhou-cv/Awesome-Text-to-Image](https://github.com/Yutong-Zhou-cv/Awesome-Text-to-Image)`

---

## 目录

- [更新日志](#更新日志)
- [如何贡献](#如何贡献)
- [阅读方式与条目格式](#阅读方式与条目格式)
- [主题总览（建议分类）](#主题总览建议分类)
- [精选综述 / 教程](#精选综述--教程)
- [论文（按方向）](#论文按方向)
  - [可视化基础与设计理论](#可视化基础与设计理论)
  - [可视分析与交互](#可视分析与交互)
  - [可解释性与模型可视化](#可解释性与模型可视化)
  - [图可视化 / 网络可视化](#图可视化--网络可视化)
  - [时序与事件序列可视化](#时序与事件序列可视化)
  - [高维数据可视化与降维](#高维数据可视化与降维)
  - [不确定性可视化](#不确定性可视化)
  - [科学可视化（体渲染/流场/医学等）](#科学可视化体渲染流场医学等)
  - [地理空间与时空可视化](#地理空间与时空可视化)
  - [文本/多模态可视化](#文本多模态可视化)
  - [评测、基准与复现](#评测基准与复现)
- [数据集与基准](#数据集与基准)
- [工具 / 系统 / 开源项目](#工具--系统--开源项目)
- [课程 / 书籍 / 博客](#课程--书籍--博客)
- [相关 Awesome](#相关-awesome)
- [许可证](#许可证)

---

## 更新日志

- **2026-03-26**：初始化仓库结构与 `README.md` 骨架。

---

## 如何贡献

欢迎 PR / Issue。贡献方式请先阅读 `[CONTRIBUTING.md](./CONTRIBUTING.md)`。

你也可以直接提 Issue：

- **补充论文**：给出题目 + 链接（arXiv/会议/Project/Code）
- **修正信息**：作者/会议/年份/链接/分类错误
- **新增分类**：当条目超过一定规模时再拆分更清晰

---

## 阅读方式与条目格式

### 条目推荐格式

统一用下面格式，方便检索与维护：

- (会议/期刊 年份) **论文标题**，First Author et al. [[Paper]](链接) [[Project]](链接) [[Code]](链接) `Tags: xxx, yyy`

示例（占位）：

- (VIS 20XX) **A Great Visualization Paper**，Author et al. [[Paper]](https://example.com) [[Code]](https://github.com/example/repo) `Tags: interaction, evaluation`

### 贡献者常用约定

- **Paper**：优先 official PDF / arXiv / publisher 页面
- **Code**：优先官方仓库；如为复现请标注 `Reproduction`
- **Project**：项目页 / Demo / 视频
- **Tags**：简短、可检索（建议 2-5 个）

### 同一条目的“唯一 ID”与交叉引用（强烈推荐）

当同一篇论文同时属于多个类别时，建议采用“**主条目 + cross-ref**”结构，避免重复维护：

- **主条目**：只在一个最合适的类别里写完整信息，并在条目前加一个唯一锚点：`<a id="paper-id"></a>`
- **交叉引用**：在其他类别里只写一行指向主条目：`[见主条目](#paper-id)`

`paper-id` 建议用稳定、可读的格式，比如：`venue-year-firstauthor-keyword`（示例：`vis-2025-smith-chartqa`）。

---

## 主题总览（建议分类）

> 你可以先按“方向”填充。后续当量变大，我们再补“按年份（2026/2025/…）”的索引页或拆分到 `Lists/` 目录。

- **理论与设计**：可视化设计空间、感知、叙事、可视化语法
- **交互与可视分析**：交互范式、分析流程、系统与用户研究
- **可解释性**：XAI 可视化、模型诊断、调试与对齐
- **图与网络**：图布局、动态图、属性图、可视分析
- **时序**：时间序列、事件序列、因果、对齐与聚类可视化
- **高维与嵌入**：降维、投影、可视聚类与表示学习
- **不确定性**：不确定性编码、传播、交互决策
- **科学可视化**：体渲染、流场、医学影像、仿真可视化
- **地理时空**：地图、轨迹、空间统计、城市计算可视化
- **文本/多模态**：文档集合、对话、跨模态解释与分析
- **评测**：基准、度量、用户实验方法学、可复现性

---

## 精选综述 / 教程

> 先放你认可的“必读”综述/教程；后续可按方向拆分。

| Year | Venue | Title | Paper | Project | Code | Tags |
| --- | --- | --- | --- | --- | --- | --- |
| 20XX | Survey/Tutorial | Title | [[Paper]](link) | [[Project]](link) | [[Code]](link) | survey, tutorial |

---

## 论文（按方向）

### 可视化基础与设计理论

| Year | Venue | Title | Paper | Project | Code | Tags |
| --- | --- | --- | --- | --- | --- | --- |
| 20XX | Venue | Title | [[Paper]](link) | [[Project]](link) | [[Code]](link) | theory, perception, design |

### 可视分析与交互

| Year | Venue | Title | Paper | Project | Code | Tags |
| --- | --- | --- | --- | --- | --- | --- |
| 20XX | Venue | Title | [[Paper]](link) | [[Project]](link) | [[Code]](link) | interaction, visual-analytics, system |

### 可解释性与模型可视化

| Year | Venue | Title | Paper | Project | Code | Tags |
| --- | --- | --- | --- | --- | --- | --- |
| 20XX | Venue | Title | [[Paper]](link) | [[Project]](link) | [[Code]](link) | explainability, model-understanding |

### 图可视化 / 网络可视化

| Year | Venue | Title | Paper | Project | Code | Tags |
| --- | --- | --- | --- | --- | --- | --- |
| 20XX | Venue | Title | [[Paper]](link) | [[Project]](link) | [[Code]](link) | graph, network |

### 时序与事件序列可视化

| Year | Venue | Title | Paper | Project | Code | Tags |
| --- | --- | --- | --- | --- | --- | --- |
| 20XX | Venue | Title | [[Paper]](link) | [[Project]](link) | [[Code]](link) | time-series, event-sequence |

### 高维数据可视化与降维

| Year | Venue | Title | Paper | Project | Code | Tags |
| --- | --- | --- | --- | --- | --- | --- |
| 20XX | Venue | Title | [[Paper]](link) | [[Project]](link) | [[Code]](link) | dimensionality-reduction, embedding |

### 不确定性可视化

| Year | Venue | Title | Paper | Project | Code | Tags |
| --- | --- | --- | --- | --- | --- | --- |
| 20XX | Venue | Title | [[Paper]](link) | [[Project]](link) | [[Code]](link) | uncertainty |

### 科学可视化（体渲染/流场/医学等）

| Year | Venue | Title | Paper | Project | Code | Tags |
| --- | --- | --- | --- | --- | --- | --- |
| 20XX | Venue | Title | [[Paper]](link) | [[Project]](link) | [[Code]](link) | scivis, volume-rendering, flow |

### 地理空间与时空可视化

| Year | Venue | Title | Paper | Project | Code | Tags |
| --- | --- | --- | --- | --- | --- | --- |
| 20XX | Venue | Title | [[Paper]](link) | [[Project]](link) | [[Code]](link) | geo, spatiotemporal |

### 文本/多模态可视化

> 这里主要收录 **Visualization × NLP/MLLM/Multimodal** 的研究：例如图表理解、视觉问答、从可视化中抽取结构化信息、LLM 辅助可视分析等。

| Year | Venue | Title | Paper | Project | Code | Tags |
| --- | --- | --- | --- | --- | --- | --- |
| 2025 | arXiv | SimVecVis: A Dataset for Enhancing MLLMs in Visualization Understanding *(cross-ref)* | [见主条目](#simvecvis) | - | - | chart, mllm, vis-understanding |
| 20XX | Venue | Title | [[Paper]](link) | [[Project]](link) | [[Code]](link) | tag1, tag2 |

### 评测方法学与复现（Evaluation & Reproducibility）

> 这里放“**怎么评测**/用户研究方法学/度量指标/复现研究/对比与诊断”等论文与实践。
> “可下载可复用的数据资源与 benchmark 套件”请放在下方的「数据集与 Benchmark Suites」。

| Year | Venue | Title | Paper | Project | Code | Tags |
| --- | --- | --- | --- | --- | --- | --- |
| 2025 | arXiv | SimVecVis: A Dataset for Enhancing MLLMs in Visualization Understanding *(cross-ref)* | [见主条目](#simvecvis) | - | - | dataset, benchmark, evaluation |
| 20XX | Venue | Title | [[Paper]](link) | [[Project]](link) | [[Code]](link) | evaluation, reproducibility |

---

## 数据集与 Benchmark Suites

> 这里主要收录**可复用的数据资源（datasets）**与**成体系的评测基准/套件（benchmark suites）**（通常包含数据 + 任务/协议 + 指标，最好还有代码）。
> 评测方法学与复现类论文请放在上面的「评测方法学与复现」。

### 2025

<a id="simvecvis"></a>

| Year | Venue | Title | Paper | Project | Code | Tags |
| --- | --- | --- | --- | --- | --- | --- |
| 2025 | arXiv | SimVecVis: A Dataset for Enhancing MLLMs in Visualization Understanding | [[Paper]](https://arxiv.org/abs/2506.21319) | - | - | dataset, chart, mllm, vis-understanding |

### 其他年份（占位）

| Year | Venue | Title | Paper | Project | Code | Tags |
| --- | --- | --- | --- | --- | --- | --- |
| 20XX | Venue | Title | [[Paper]](link) | [[Project]](link) | [[Code]](link) | tag1, tag2 |

---

## 工具 / 系统 / 开源项目

> 既可以放研究系统（paper+code），也可以放工程工具链（渲染、Web 可视化、交互框架等）。

| Name | Type | Link | Description | Tags |
| --- | --- | --- | --- | --- |
| Name | Repo/Tool/System | [[Link]](link) | 一句话描述 | tool |

---

## 课程 / 书籍 / 博客

### Courses

| Name | Link | Notes |
| --- | --- | --- |
| Course Name | [[Link]](link) | - |

### Books

| Year | Title | Link | Notes |
| --- | --- | --- | --- |
| 20XX | Book Name | [[Link]](link) | - |

### Blogs / Tutorials

| Title | Link | Notes |
| --- | --- | --- |
| Title | [[Link]](link) | - |

---

## 相关 Awesome

> 你后续可以补充更多同类 “Awesome / Survey repo” 作为互链。

- `[AlonzoLeeeooo/awesome-video-generation](https://github.com/AlonzoLeeeooo/awesome-video-generation)`
- `[tandaily/Awesome-Relighting](https://github.com/tandaily/Awesome-Relighting)`
- `[MarkMoHR/Awesome-Sketch-Based-Applications](https://github.com/MarkMoHR/Awesome-Sketch-Based-Applications)`
- `[Yutong-Zhou-cv/Awesome-Text-to-Image](https://github.com/Yutong-Zhou-cv/Awesome-Text-to-Image)`

---

## 许可证

待定（如果你希望对齐常见 Awesome 项目，可选 MIT License）。