# mixtral-8x7b-32kseqlen

> Large Language Model

**Organization:** [Mistral](../../labs/mistral.md)
**Released:** Dec/2023
**Access:** 🟢 Public

---

## 📊 Overview

mixtral-8x7b-32kseqlen is a large language model developed by Mistral.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 46.7B
- **Training Tokens:** 8000.0B
- **Token:Param Ratio:** 172:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 2.0 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 70.6 | General knowledge across 57 subjects |
| **MMLU-Pro** | 43.3 | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

MoE=7Bx8, aka mistral-small. 'Concretely, Mixtral has 45B total parameters but only uses 12B parameters per token. It, therefore, processes input and generates output at the same speed and for the same cost as a 12B model.'

## 🔗 Resources

- 🎮 [Try the Model](https://www.together.ai/blog/mixtral)
- 📄 [Technical Documentation](https://arxiv.org/abs/2401.04088)

## 🔍 Related Models

**From Mistral:**
- See all models in [Mistral profile](../../labs/mistral.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Mistral Models](../../labs/mistral.md)
