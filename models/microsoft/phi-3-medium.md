# phi-3-medium

> Large Language Model

**Organization:** [Microsoft](../../labs/microsoft.md)
**Released:** Apr/2024
**Access:** 🟢 Public

---

## 📊 Overview

phi-3-medium is a large language model developed by Microsoft.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 14.0B
- **Training Tokens:** 4800.0B
- **Token:Param Ratio:** 343:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.9 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 78.2 | General knowledge across 57 subjects |
| **MMLU-Pro** | 55.7 | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Preview only, benchmarks being investigated as of May/2024.

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/microsoft/Phi-3-medium-128k-instruct)
- 📄 [Technical Documentation](https://arxiv.org/abs/2404.14219)

## 🔍 Related Models

**From Microsoft:**
- See all models in [Microsoft profile](../../labs/microsoft.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Microsoft Models](../../labs/microsoft.md)
