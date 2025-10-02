# AlexaTM 20B

> Large Language Model

**Organization:** [Amazon](../../labs/amazon.md)
**Released:** Aug/2022
**Access:** 🟢 Public

---

## 📊 Overview

AlexaTM 20B is a large language model developed by Amazon.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 20.0B
- **Training Tokens:** 1300.0B
- **Token:Param Ratio:** 65:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.5 (Lightweight)
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

Wikipedia and mC4 only. seq2seq

## 🔗 Resources

- 🎮 [Try the Model](Github (train/deploy))
- 📄 [Technical Documentation](https://assets.amazon.science/ee/20/3abcf2304d9b8d68da2006ff7107/alexatm-20b-few-shot-learning-using-a-large-scale-multilingual-seq2seq-model.pdf)

## 🔍 Related Models

**From Amazon:**
- See all models in [Amazon profile](../../labs/amazon.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Amazon Models](../../labs/amazon.md)
