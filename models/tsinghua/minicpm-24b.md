# MiniCPM-2.4B

> Large Language Model

**Organization:** [Tsinghua](../../labs/tsinghua.md)
**Released:** Apr/2024
**Access:** 🟢 Public

---

## 📊 Overview

MiniCPM-2.4B is a large language model developed by Tsinghua.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 2.4B
- **Training Tokens:** 1100.0B
- **Token:Param Ratio:** 459:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.2 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

MoE option=https://huggingface.co/openbmb/MiniCPM-MoE-8x2B

## 🔗 Resources

- 🎮 [Try the Model](https://github.com/OpenBMB/MiniCPM/)
- 📄 [Technical Documentation](https://arxiv.org/abs/2404.06395)

## 🔍 Related Models

**From Tsinghua:**
- See all models in [Tsinghua profile](../../labs/tsinghua.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Tsinghua Models](../../labs/tsinghua.md)
