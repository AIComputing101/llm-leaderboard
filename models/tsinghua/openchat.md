# OpenChat

> Large Language Model

**Organization:** [Tsinghua](../../labs/tsinghua.md)
**Released:** Sep/2022
**Access:** 🟢 Public

---

## 📊 Overview

OpenChat is a large language model developed by Tsinghua.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 13.0B
- **Training Tokens:** 2000.0B
- **Token:Param Ratio:** 154:1 ✅ Compute-optimal

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

Llama 2 13B -> OpenChat 13B

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/openchat/openchat_3.5)
- 📄 [Technical Documentation](https://arxiv.org/abs/2309.11235)

## 🔍 Related Models

**From Tsinghua:**
- See all models in [Tsinghua profile](../../labs/tsinghua.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Tsinghua Models](../../labs/tsinghua.md)
