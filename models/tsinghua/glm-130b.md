# GLM-130B

> Large Language Model

**Organization:** [Tsinghua](../../labs/tsinghua.md)
**Released:** Aug/2022
**Access:** 🟢 Public

---

## 📊 Overview

GLM-130B is a large language model developed by Tsinghua.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 130.0B
- **Training Tokens:** 400.0B
- **Token:Param Ratio:** 4:1 ⚠️ Under-trained

### Training Efficiency
- **ALScore:** 0.8 (Lightweight)
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

50% English (200B tokens), so included here

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/spaces/THUDM/GLM-130B)
- 📄 [Technical Documentation](https://arxiv.org/abs/2210.02414)

## 🔍 Related Models

**From Tsinghua:**
- See all models in [Tsinghua profile](../../labs/tsinghua.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Tsinghua Models](../../labs/tsinghua.md)
