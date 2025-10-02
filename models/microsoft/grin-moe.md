# GRIN MoE

> Large Language Model

**Organization:** [Microsoft](../../labs/microsoft.md)
**Released:** Sep/2024
**Access:** 🟢 Public

---

## 📊 Overview

GRIN MoE is a large language model developed by Microsoft.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 60.0B
- **Training Tokens:** 4025.0B
- **Token:Param Ratio:** 68:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 1.6 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 79.4 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

16x3.8B "only 6.6B activate parameters". GRIN=GRadient-INformed. "GRIN MoE is pre-trained on 4T tokens as a Causal Language Model. The same training dataset has been used to train Phi-3 dense models"

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/microsoft/GRIN-MoE)
- 📄 [Technical Documentation](https://huggingface.co/microsoft/GRIN-MoE/blob/main/GRIN_MoE.pdf)

## 🔍 Related Models

**From Microsoft:**
- See all models in [Microsoft profile](../../labs/microsoft.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Microsoft Models](../../labs/microsoft.md)
