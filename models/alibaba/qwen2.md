# Qwen2

> Large Language Model

**Organization:** [Alibaba](../../labs/alibaba.md)
**Released:** Jun/2024
**Access:** 🟢 Public

---

## 📊 Overview

Qwen2 is a large language model developed by Alibaba.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 72.0B
- **Training Tokens:** 7000.0B
- **Token:Param Ratio:** 98:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 2.4 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 84.2 | General knowledge across 57 subjects |
| **MMLU-Pro** | 55.6 | Advanced MMLU variant |
| **GPQA** | 37.9 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Instruct MMLU=82. Instruct GPQA=41.9. https://qwenlm.github.io/blog/qwen2/

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/spaces/Qwen/Qwen2-72B-Instruct)
- 📄 [Technical Documentation](https://arxiv.org/abs/2407.10671)

## 🔍 Related Models

**From Alibaba:**
- See all models in [Alibaba profile](../../labs/alibaba.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Alibaba Models](../../labs/alibaba.md)
