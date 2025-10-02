# KAT-V1-40B

> Reasoning

**Organization:** [Kuaishou](../../labs/kuaishou.md)
**Released:** Jul/2025
**Access:** 🟢 Public

---

## 📊 Overview

KAT-V1-40B is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 40.0B
- **Training Tokens:** 10000.0B
- **Token:Param Ratio:** 250:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 2.1 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | 77.8 | Advanced MMLU variant |
| **GPQA** | 75.1 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

"to address the overthinking problem in reasoning-intensive tasks"

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/Kwaipilot/KAT-V1-40B)
- 📄 [Technical Documentation](https://arxiv.org/abs/2507.08297)

## 🔍 Related Models

**From Kuaishou:**
- See all models in [Kuaishou profile](../../labs/kuaishou.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Kuaishou Models](../../labs/kuaishou.md)
