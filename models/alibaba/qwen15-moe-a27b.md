# Qwen1.5-MoE-A2.7B

> Large Language Model

**Organization:** [Alibaba](../../labs/alibaba.md)
**Released:** Mar/2024
**Access:** 🟢 Public

---

## 📊 Overview

Qwen1.5-MoE-A2.7B is a large language model developed by Alibaba.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 14.3B
- **Training Tokens:** 1500.0B
- **Token:Param Ratio:** 105:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.5 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 62.5 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

MoE. "Of particular significance is the fact that, through upcycling, the necessity for training an equivalent volume of tokens as in the original model has been eliminated." I assumed half of the original 3T tokens

## 🔗 Resources

- 🎮 [Try the Model](https://qwenlm.github.io/blog/qwen-moe/)
- 📄 [Technical Documentation](https://qwenlm.github.io/blog/qwen-moe/)

## 🔍 Related Models

**From Alibaba:**
- See all models in [Alibaba profile](../../labs/alibaba.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Alibaba Models](../../labs/alibaba.md)
