# Phi-4

> SOTA

**Organization:** [Microsoft](../../labs/microsoft.md)
**Released:** Dec/2024
**Access:** 🟢 Public

---

## 📊 Overview

Phi-4 represents state-of-the-art performance in its category.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 14.0B
- **Training Tokens:** 10000.0B
- **Token:Param Ratio:** 715:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 1.2 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 84.8 | General knowledge across 57 subjects |
| **MMLU-Pro** | 70.4 | Advanced MMLU variant |
| **GPQA** | 56.1 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

## 🏷️ Model Tags

`SOTA`

## 📝 Additional Notes

Use unsloth: https://huggingface.co/unsloth/phi-4-GGUF & https://www.reddit.com/r/singularity/comments/1i0kso4/i_fixed_4_bugs_in_microsofts_opensource_phi4_model/

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/microsoft/phi-4)
- 📄 [Technical Documentation](https://arxiv.org/abs/2412.08905)

## 🔍 Related Models

**From Microsoft:**
- See all models in [Microsoft profile](../../labs/microsoft.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Microsoft Models](../../labs/microsoft.md)
