# YAYI 2

> Large Language Model

**Organization:** [Wenge](../../labs/wenge.md)
**Released:** Dec/2023
**Access:** 🟢 Public

---

## 📊 Overview

YAYI 2 is a large language model developed by Wenge.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 30.0B
- **Training Tokens:** 2650.0B
- **Token:Param Ratio:** 89:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.9 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 80.5 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Dataset=240TB filtered to 10.6TB for 2.65T tokens

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/wenge-research/yayi2-30b)
- 📄 [Technical Documentation](https://arxiv.org/abs/2312.14862)

## 🔍 Related Models

**From Wenge:**
- See all models in [Wenge profile](../../labs/wenge.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Wenge Models](../../labs/wenge.md)
