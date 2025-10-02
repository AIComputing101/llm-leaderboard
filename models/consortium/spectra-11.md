# Spectra 1.1

> Large Language Model

**Organization:** [Consortium](../../labs/consortium.md)
**Released:** Jun/2025
**Access:** 🟢 Public

---

## 📊 Overview

Spectra 1.1 is a large language model developed by Consortium.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 3.6B
- **Training Tokens:** 1200.0B
- **Token:Param Ratio:** 334:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.2 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 36.12 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

"Spectra-1.1, an open suite of TriLMs trained on up to 1.2 trillion tokens, demonstrating sustained performance gains at scale. Furthermore, to improve inference efficiency, we propose novel 2-bit and 1.6-bit packing schemes for ternary weights"

## 🔗 Resources

- 📄 [Technical Documentation](https://arxiv.org/abs/2506.23025)

## 🔍 Related Models

**From Consortium:**
- See all models in [Consortium profile](../../labs/consortium.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Consortium Models](../../labs/consortium.md)
