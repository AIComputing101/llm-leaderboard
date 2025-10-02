# phi-3-mini

> Large Language Model

**Organization:** [Microsoft](../../labs/microsoft.md)
**Released:** Apr/2024
**Access:** 🟢 Public

---

## 📊 Overview

phi-3-mini is a large language model developed by Microsoft.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 3.8B
- **Training Tokens:** 3300.0B
- **Token:Param Ratio:** 869:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.4 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 68.8 | General knowledge across 57 subjects |
| **MMLU-Pro** | 45.7 | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

"phi3-mini can be quantized to 4-bits so that it only occupies ≈ 1.8GB of memory. We tested the quantized model by deploying phi-3-mini on iPhone 14 with A16 Bionic chip running natively on-device and fully offline achieving more than 12 tokens per second."

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/microsoft/Phi-3-mini-128k-instruct)
- 📄 [Technical Documentation](https://arxiv.org/abs/2404.14219)

## 🔍 Related Models

**From Microsoft:**
- See all models in [Microsoft profile](../../labs/microsoft.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Microsoft Models](../../labs/microsoft.md)
