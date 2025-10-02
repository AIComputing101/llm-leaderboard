# MM1

> Large Language Model

**Organization:** [Apple](../../labs/apple.md)
**Released:** Mar/2024
**Access:** 🔴 Private

---

## 📊 Overview

MM1 is a large language model developed by Apple.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 30.0B
- **Training Tokens:** 2010.0B
- **Token:Param Ratio:** 67:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.8 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** special

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

VLM, outperforms Flamingo 80B (Apr/2022) across benchmarks. 2T text tokens + ~10B+ other text (estimate). Unreleased.

## 🔗 Resources

- 📄 [Technical Documentation](https://arxiv.org/abs/2403.09611)

## 🔍 Related Models

**From Apple:**
- See all models in [Apple profile](../../labs/apple.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Apple Models](../../labs/apple.md)
