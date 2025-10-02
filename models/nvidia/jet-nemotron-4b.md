# Jet-Nemotron-4B

> Reasoning

**Organization:** [NVIDIA](../../labs/nvidia.md)
**Released:** Aug/2025
**Access:** 🟢 Public

---

## 📊 Overview

Jet-Nemotron-4B is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 4.0B
- **Training Tokens:** 400.0B
- **Token:Param Ratio:** 100:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.1 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 65.2 | General knowledge across 57 subjects |
| **MMLU-Pro** | 44.2 | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

"pre-training corpus and train Jet-Nemotron models for 50B tokens. This is also the setting in Section 2 where we perform PostNAS. At the second stage, we include more high-quality data from math [65] and coding [66, 67] domains into our data mixture. The models are then trained on 350B tokens."

## 🔗 Resources

- 🎮 [Try the Model](https://github.com/NVlabs/Jet-Nemotron)
- 📄 [Technical Documentation](https://arxiv.org/abs/2508.15884v1)

## 🔍 Related Models

**From NVIDIA:**
- See all models in [NVIDIA profile](../../labs/nvidia.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All NVIDIA Models](../../labs/nvidia.md)
