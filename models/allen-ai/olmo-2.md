# OLMo 2

> Large Language Model

**Organization:** [Allen AI](../../labs/allen-ai.md)
**Released:** Nov/2024
**Access:** 🟢 Public

---

## 📊 Overview

OLMo 2 is a large language model developed by Allen AI.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 13.0B
- **Training Tokens:** 5600.0B
- **Token:Param Ratio:** 431:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.9 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 68.6 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Open Language Model (OLMo) 2 Apache 2.0 license for research and educational use. Paper coming. Data: 5 trillion tokens (1.2 epochs of 4T tokens) + 100B tokens (3 runs) + 300B tokens (1 run) merged. https://huggingface.co/allenai/OLMo-2-1124-13B & playground: https://playground.allenai.org/

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/collections/allenai/olmo-2-674117b93ab84e98afc72edc)
- 📄 [Technical Documentation](https://arxiv.org/abs/2501.00656)

## 🔍 Related Models

**From Allen AI:**
- See all models in [Allen AI profile](../../labs/allen-ai.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Allen AI Models](../../labs/allen-ai.md)
