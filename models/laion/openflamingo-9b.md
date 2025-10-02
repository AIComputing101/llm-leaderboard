# OpenFlamingo-9B

> Large Language Model

**Organization:** [LAION](../../labs/laion.md)
**Released:** Mar/2023
**Access:** 🟢 Public

---

## 📊 Overview

OpenFlamingo-9B is a large language model developed by LAION.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 8.3B
- **Training Tokens:** 1000.0B
- **Token:Param Ratio:** 121:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.3 (Lightweight)
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

Uses LLaMA-7B. Demo: https://7164d2142d11.ngrok.app/

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/openflamingo/OpenFlamingo-9B)
- 📄 [Technical Documentation](https://laion.ai/blog/open-flamingo/)

## 🔍 Related Models

**From LAION:**
- See all models in [LAION profile](../../labs/laion.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All LAION Models](../../labs/laion.md)
