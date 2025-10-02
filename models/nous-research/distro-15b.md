# DisTrO 15B

> Large Language Model

**Organization:** [Nous Research](../../labs/nous-research.md)
**Released:** Dec/2024
**Access:** 🟢 Public

---

## 📊 Overview

DisTrO 15B is a large language model developed by Nous Research.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 15.0B
- **Training Tokens:** 100.0B
- **Token:Param Ratio:** 7:1 ⚠️ Under-trained

### Training Efficiency
- **ALScore:** 0.1 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 23.48 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

"About 14 DGXes scattered around the globe. Sometimes more sometimes less, it varies depending on availability. On average, around 112 H100s." https://x.com/bloc97_/status/1863675225810043331 "we introduce DisTrO, a family of architecture-agnostic and network-agnostic distributed optimizers that reduces the inter-GPU communication requirements by four to five orders of magnitude without relying on amortized analysis, enabling low-latency training of large neural networks on slow internet bandwidths with heterogeneous networking hardware."

## 🔗 Resources

- 🎮 [Try the Model](https://distro.nousresearch.com/)
- 📄 [Technical Documentation](https://github.com/NousResearch/DisTrO?tab=readme-ov-file)

## 🔍 Related Models

**From Nous Research:**
- See all models in [Nous Research profile](../../labs/nous-research.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Nous Research Models](../../labs/nous-research.md)
