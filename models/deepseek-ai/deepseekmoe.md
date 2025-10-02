# DeepSeekMoE

> Large Language Model

**Organization:** [DeepSeek-AI](../../labs/deepseek-ai.md)
**Released:** Jan/2024
**Access:** 🔴 Private

---

## 📊 Overview

DeepSeekMoE is a large language model developed by DeepSeek-AI.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 16.0B
- **Training Tokens:** 2000.0B
- **Token:Param Ratio:** 125:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.6 (Lightweight)
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

MoE activated parameters is 10-15% of dense, so I need to rethink ALScore for MoE. 'preliminary efforts to scale up DeepSeekMoE to 145B'

## 🔗 Resources

- 📄 [Technical Documentation](https://arxiv.org/abs/2401.06066)

## 🔍 Related Models

**From DeepSeek-AI:**
- See all models in [DeepSeek-AI profile](../../labs/deepseek-ai.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All DeepSeek-AI Models](../../labs/deepseek-ai.md)
