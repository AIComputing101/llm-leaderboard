# Apple On-Device model Jun/2024

> Large Language Model

**Organization:** [Apple](../../labs/apple.md)
**Released:** Jun/2024
**Access:** 🟢 Public

---

## 📊 Overview

Apple On-Device model Jun/2024 is a large language model developed by Apple.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 3.04B
- **Training Tokens:** 1500.0B
- **Token:Param Ratio:** 494:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.2 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 26.76 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Likely to be the Apple OpenELM model (Apr/2024). "two of these models — a ~3 billion parameter on-device language model, and a larger server-based language model available with Private Cloud Compute". https://machinelearning.apple.com/research/introducing-apple-foundation-models The server-based model is possibly Ferret, although it is more properly called a multimodal model (not just language). It could also be Apple GPT based on their Ajax framework: https://archive.md/f3C0r

## 🔗 Resources

- 🎮 [Try the Model](https://github.com/apple/corenet/tree/main/projects/openelm)
- 📄 [Technical Documentation](https://arxiv.org/abs/2404.14619)

## 🔍 Related Models

**From Apple:**
- See all models in [Apple profile](../../labs/apple.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Apple Models](../../labs/apple.md)
