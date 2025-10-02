# TinyLlama

> Large Language Model

**Organization:** [SUTD/Independent](../../labs/sutdindependent.md)
**Released:** Jan/2024
**Access:** 🟢 Public

---

## 📊 Overview

TinyLlama is a large language model developed by SUTD/Independent.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 1.1B
- **Training Tokens:** 3000.0B
- **Token:Param Ratio:** 2,728:1 ✅ Compute-optimal

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

Overtrained' using 2,727 tokens per parameter. Dataset was 1T: 3 epochs to 3T seen. Singapore

## 🔗 Resources

- 🎮 [Try the Model](https://github.com/jzhang38/TinyLlama)
- 📄 [Technical Documentation](https://arxiv.org/abs/2401.02385)

## 🔍 Related Models

**From SUTD/Independent:**
- See all models in [SUTD/Independent profile](../../labs/sutdindependent.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All SUTD/Independent Models](../../labs/sutdindependent.md)
