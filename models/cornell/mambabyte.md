# MambaByte

> Large Language Model

**Organization:** [Cornell](../../labs/cornell.md)
**Released:** Jan/2024
**Access:** 🔴 Private

---

## 📊 Overview

MambaByte is a large language model developed by Cornell.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 0.972B
- **Training Tokens:** 37.5B
- **Token:Param Ratio:** 39:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.0
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** books, code

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

Used bytes instead of tokens. 4 bytes≈1 token, so 150B bytes≈37.5B tokens

## 🔗 Resources

- 🎮 [Try the Model](https://github.com/kyegomez/MambaByte)
- 📄 [Technical Documentation](https://arxiv.org/abs/2401.13660)

## 🔍 Related Models

**From Cornell:**
- See all models in [Cornell profile](../../labs/cornell.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Cornell Models](../../labs/cornell.md)
