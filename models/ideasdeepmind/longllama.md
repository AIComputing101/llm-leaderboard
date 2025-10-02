# LongLLaMA

> Large Language Model

**Organization:** [IDEAS/DeepMind](../../labs/ideasdeepmind.md)
**Released:** Jul/2023
**Access:** 🟢 Public

---

## 📊 Overview

LongLLaMA is a large language model developed by IDEAS/DeepMind.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 7.0B
- **Training Tokens:** 1000.0B
- **Token:Param Ratio:** 143:1 ✅ Compute-optimal

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

256k context length

## 🔗 Resources

- 🎮 [Try the Model](https://github.com/CStanKonrad/long_llama)
- 📄 [Technical Documentation](https://arxiv.org/abs/2307.03170)

## 🔍 Related Models

**From IDEAS/DeepMind:**
- See all models in [IDEAS/DeepMind profile](../../labs/ideasdeepmind.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All IDEAS/DeepMind Models](../../labs/ideasdeepmind.md)
