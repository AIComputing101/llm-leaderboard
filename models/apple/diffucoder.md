# DiffuCoder

> Diffusion

**Organization:** [Apple](../../labs/apple.md)
**Released:** Jun/2025
**Access:** 🟢 Public

---

## 📊 Overview

DiffuCoder is a large language model developed by Apple.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 7.0B
- **Training Tokens:** 5630.0B
- **Token:Param Ratio:** 805:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.7 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** code, The Stack

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

`Diffusion`

## 📝 Additional Notes

"We adapt our model from Qwen2.5-Coder (Hui et al., 2024) as the base model to perform continual pre-training using the adaptation approach from Gong et al. (2025). During this pre-training, we use a 400B-token code pre-training corpus from RefineCode (Huang et al., 2024) and Stackv2 (Lozhkov et al., 2024)."

## 🔗 Resources

- 🎮 [Try the Model](https://github.com/apple/ml-diffucoder)
- 📄 [Technical Documentation](https://arxiv.org/abs/2506.20639)

## 🔍 Related Models

**From Apple:**
- See all models in [Apple profile](../../labs/apple.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Apple Models](../../labs/apple.md)
