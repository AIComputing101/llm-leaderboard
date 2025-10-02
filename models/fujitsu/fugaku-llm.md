# Fugaku-LLM

> Large Language Model

**Organization:** [Fujitsu](../../labs/fujitsu.md)
**Released:** May/2024
**Access:** 🟢 Public

---

## 📊 Overview

Fugaku-LLM is a large language model developed by Fujitsu.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 13.0B
- **Training Tokens:** 380.0B
- **Token:Param Ratio:** 30:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.2 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Japanese. CPU trained: 158,976+ A64FX CPUs (7M+ cores), zero GPUs. https://en.wikipedia.org/wiki/Fugaku_(supercomputer)

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/Fugaku-LLM/Fugaku-LLM-13B-instruct)
- 📄 [Technical Documentation](https://www.fujitsu.com/global/about/resources/news/press-releases/2024/0510-01.html)

## 🔍 Related Models

**From Fujitsu:**
- See all models in [Fujitsu profile](../../labs/fujitsu.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Fujitsu Models](../../labs/fujitsu.md)
