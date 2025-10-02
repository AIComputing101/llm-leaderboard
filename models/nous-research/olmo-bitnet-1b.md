# OLMo-Bitnet-1B

> Large Language Model

**Organization:** [Nous Research](../../labs/nous-research.md)
**Released:** Apr/2024
**Access:** 🟢 Public

---

## 📊 Overview

OLMo-Bitnet-1B is a large language model developed by Nous Research.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 1.0B
- **Training Tokens:** 60.0B
- **Token:Param Ratio:** 60:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.0
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

1.58-bit quantized (ternary weights) means we can run a 70B model in ~14GB VRAM. See also BitNet b1.58

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/NousResearch/OLMo-Bitnet-1B)
- 📄 [Technical Documentation](https://arxiv.org/abs/2402.17764)

## 🔍 Related Models

**From Nous Research:**
- See all models in [Nous Research profile](../../labs/nous-research.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Nous Research Models](../../labs/nous-research.md)
