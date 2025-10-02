# Klear-46B-A2.5B

> Large Language Model

**Organization:** [Kuaishou](../../labs/kuaishou.md)
**Released:** Sep/2025
**Access:** 🟢 Public

---

## 📊 Overview

Klear-46B-A2.5B is a large language model developed by Kuaishou.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 46.0B
- **Training Tokens:** 22000.0B
- **Token:Param Ratio:** 479:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 3.4 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 80.5 | General knowledge across 57 subjects |
| **MMLU-Pro** | 57.6 | Advanced MMLU variant |
| **GPQA** | 35.3 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

46B-A2.5B.

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/Kwai-Klear/Klear-46B-A2.5B-Instruct)
- 📄 [Technical Documentation](https://huggingface.co/Kwai-Klear/Klear-46B-A2.5B-Instruct)

## 🔍 Related Models

**From Kuaishou:**
- See all models in [Kuaishou profile](../../labs/kuaishou.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Kuaishou Models](../../labs/kuaishou.md)
