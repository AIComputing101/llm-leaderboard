# phi-3.5-MoE

> Large Language Model

**Organization:** [Microsoft](../../labs/microsoft.md)
**Released:** Aug/2024
**Access:** 🟢 Public

---

## 📊 Overview

phi-3.5-MoE is a large language model developed by Microsoft.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 60.0B
- **Training Tokens:** 4900.0B
- **Token:Param Ratio:** 82:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 1.8 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 78.9 | General knowledge across 57 subjects |
| **MMLU-Pro** | 54.3 | Advanced MMLU variant |
| **GPQA** | 36.8 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

_No additional notes available._

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/microsoft/Phi-3.5-MoE-instruct)
- 📄 [Technical Documentation](https://arxiv.org/abs/2407.13833https://arxiv.org/abs/2407.13833)

## 🔍 Related Models

**From Microsoft:**
- See all models in [Microsoft profile](../../labs/microsoft.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Microsoft Models](../../labs/microsoft.md)
