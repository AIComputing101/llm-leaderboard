# MAI-DS-R1

> Reasoning

**Organization:** [Microsoft](../../labs/microsoft.md)
**Released:** Apr/2025
**Access:** 🟢 Public

---

## 📊 Overview

MAI-DS-R1 is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 685.0B
- **Training Tokens:** 14800.0B
- **Token:Param Ratio:** 22:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 10.6 (Very powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 86.8 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

DeepSeek-R1 base. "MAI-DS-R1, a new open weights DeepSeek R1 model variant... post-trained by the Microsoft AI team to improve its responsiveness on blocked topics and its risk profile, while maintaining its reasoning capabilities and competitive performance."

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/microsoft/MAI-DS-R1)
- 📄 [Technical Documentation](https://techcommunity.microsoft.com/blog/machinelearningblog/introducing-mai-ds-r1/4405076)

## 🔍 Related Models

**From Microsoft:**
- See all models in [Microsoft profile](../../labs/microsoft.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Microsoft Models](../../labs/microsoft.md)
