<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ShulingTang/ShulingTang/main/assets/hero-dark.svg">
  <img alt="Shuling Tang — Generative Vision" src="https://raw.githubusercontent.com/ShulingTang/ShulingTang/main/assets/hero-light.svg" width="100%">
</picture>

<br>

做生成式视觉的算法研究员,工作第五年。
过去几年的主线是**图像编辑类扩散模型**:怎么让模型听懂指令、只动该动的区域、并且在工程上跑得够快。
业余把同一套方法论用在自己身上——能交给 Agent 的事,就不再手动做第二遍。

<br>

### Focus

| | |
| :-- | :-- |
| **可控图像编辑** | 指令驱动的局部编辑,身份与版面保持,人像 / 发型 / 色彩这类"差一点就假"的场景 |
| **蒸馏与加速** | 多教师 → 单学生的在线策略蒸馏;把几十步采样压到几步而不掉质量 |
| **评测** | 编辑"有没有改好"不能靠肉眼:恒等基线、成对对比、可复现的评测流水线 |
| **Agent 工具链** | 把训练、看图、记账、抓取这些重复劳动接进 LLM Agent,自己用,顺手开源 |

<br>

### How I work

- 先建基线再谈效果——没有"保持不变"的对照,所有"变好了"都是错觉
- 数据决定上限:宁可花一周清数据,不花一天调超参
- 本地能复现的才算完成;一切自动化先在冒烟集上跑通
- 记录踩过的坑,比记录成功更有用

<br>

### Toolbox

`PyTorch` · `Diffusers` · `LoRA` · `FSDP / DeepSpeed` · `CUDA` · `Docker` · `Linux` · `Claude Code / MCP` · `n8n` · `Python`

<br>

### Writing

偶尔写点东西,在 **[shulingtang.github.io](https://shulingtang.github.io)**。

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ShulingTang/ShulingTang/output/github-snake-dark.svg">
  <img alt="contribution graph" src="https://raw.githubusercontent.com/ShulingTang/ShulingTang/output/github-snake.svg" width="100%">
</picture>

<p align="right"><sub>Less, but better.</sub></p>
