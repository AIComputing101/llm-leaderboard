# Mamba

> Large Language Model

**Organization:** [CMU](../../labs/cmu.md)
**Released:** Dec/2023
**Access:** 🟢 Public

---

## 📊 Overview

Mamba is a large language model developed by CMU.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 2.8B
- **Training Tokens:** 300.0B
- **Token:Param Ratio:** 108:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.1 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 26.2 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

The Pile, new arch beyond just Transformers. 2.7B MMLU=26.2. 7B MMLU=33.3.

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/havenhq/mamba-chat)
- 📄 [Technical Documentation](https://arxiv.org/abs/2312.00752)

## 🔍 Related Models

**From CMU:**
- See all models in [CMU profile](../../labs/cmu.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All CMU Models](../../labs/cmu.md)
