<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ShulingTang/ShulingTang/main/assets/hero-dark.svg">
  <img alt="Shuling Tang — Generative Vision" src="https://raw.githubusercontent.com/ShulingTang/ShulingTang/main/assets/hero-light.svg" width="100%">
</picture>

<br>

Research engineer in generative vision, five years in.
Most of that time has gone into **instruction-based image editing with diffusion models** — getting them to understand what to change, touch nothing else, and run fast enough to ship.
Off the clock, I apply the same principle to myself: anything an agent can do, I don't do twice.

<br>

### Focus

**Controllable image editing** — instruction-driven local edits that preserve identity and layout; portraits, hair, and color are where "almost right" still looks wrong.

**Distillation & acceleration** — multi-teacher → single-student on-policy distillation; compressing dozens of sampling steps into a few without losing quality.

**Evaluation** — "did the edit work" can't be eyeballed; identity baselines, paired comparisons, and reproducible eval pipelines.

**Agentic tooling** — wiring training, image review, bookkeeping, and scraping into LLM agents. Built for myself, open-sourced along the way.

<br>

### How I work

- Baseline before claims — without a "leave it unchanged" control, every "improvement" is an illusion.
- Data sets the ceiling: a week cleaning data beats a day tuning hyperparameters.
- It's done when it reproduces locally; every automation runs on a smoke set first.
- Writing down what broke is worth more than writing down what worked.

<br>

### Toolbox

`PyTorch` · `Diffusers` · `LoRA` · `FSDP / DeepSpeed` · `CUDA` · `Docker` · `Linux` · `Claude Code / MCP` · `n8n` · `Python`

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ShulingTang/ShulingTang/output/github-snake-dark.svg">
  <img alt="contribution graph" src="https://raw.githubusercontent.com/ShulingTang/ShulingTang/output/github-snake.svg" width="100%">
</picture>

<p align="right"><sub>Less, but better.</sub></p>
