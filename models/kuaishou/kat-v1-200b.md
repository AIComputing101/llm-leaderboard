# KAT-V1-200B

> Reasoning

**Organization:** [Kuaishou](../../labs/kuaishou.md)
**Released:** Jul/2025
**Access:** 🔴 Private

---

## 📊 Overview

KAT-V1-200B is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 200.0B
- **Training Tokens:** 10000.0B
- **Token:Param Ratio:** 50:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 4.7 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | 82.3 | Advanced MMLU variant |
| **GPQA** | 78.2 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

200BA40B. In training as of Jul/2025. "to address the overthinking problem in reasoning-intensive tasks"

## 🔗 Resources

- 📄 [Technical Documentation](https://arxiv.org/abs/2507.08297)

## 🔍 Related Models

**From Kuaishou:**
- See all models in [Kuaishou profile](../../labs/kuaishou.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Kuaishou Models](../../labs/kuaishou.md)
