# Jamba 1

> Large Language Model

**Organization:** [AI21](../../labs/ai21.md)
**Released:** Mar/2024
**Access:** 🟢 Public

---

## 📊 Overview

Jamba 1 is a large language model developed by AI21.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 52.0B
- **Training Tokens:** 5000.0B
- **Token:Param Ratio:** 97:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 1.7 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 67.4 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

MoE. Open weights, licensed under Apache 2.0. Announce: https://arxiv.org/abs/2403.19887

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/ai21labs/Jamba-v0.1)
- 📄 [Technical Documentation](https://arxiv.org/abs/2403.19887)

## 🔍 Related Models

**From AI21:**
- See all models in [AI21 profile](../../labs/ai21.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All AI21 Models](../../labs/ai21.md)
