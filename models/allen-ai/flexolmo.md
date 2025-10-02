# FlexOlmo

> Large Language Model

**Organization:** [Allen AI](../../labs/allen-ai.md)
**Released:** Jul/2025
**Access:** 🟢 Public

---

## 📊 Overview

FlexOlmo is a large language model developed by Allen AI.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 37.0B
- **Training Tokens:** 4150.0B
- **Token:Param Ratio:** 113:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 1.3 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 60.4 | General knowledge across 57 subjects |
| **MMLU-Pro** | 30.9 | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

37B-A20B. "We adopt the OLMo-2 7B setup, starting from a a checkpoint pre-trained on 4T tokens and annealed for 50B tokens to produce a public expert. We then train two additional experts on math and code, each for 50B tokens, and combine them with the public expert to form a three-expert version of FLEXOLMO."

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/allenai/FlexOlmo-7x7B-1T)
- 📄 [Technical Documentation](https://arxiv.org/abs/2507.07024v1)

## 🔍 Related Models

**From Allen AI:**
- See all models in [Allen AI profile](../../labs/allen-ai.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Allen AI Models](../../labs/allen-ai.md)
