# Megatron-11B

> Large Language Model

**Organization:** [Meta AI](../../labs/meta-ai.md)
**Released:** Apr/2020
**Access:** 🟢 Public

---

## 📊 Overview

Megatron-11B is a large language model developed by Meta AI.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 11.0B
- **Training Tokens:** 2200.0B
- **Token:Param Ratio:** 200:1 ✅ Compute-optimal

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

My favourite model until GPT-3 and GPT-4 came along: https://github.com/facebookresearch/fairseq/blob/main/examples/megatron_11b/README.md

## 🔗 Resources

- 🎮 [Try the Model](InferKit)
- 📄 [Technical Documentation](https://github.com/pytorch/fairseq/tree/main/examples/megatron_11b)

## 🔍 Related Models

**From Meta AI:**
- See all models in [Meta AI profile](../../labs/meta-ai.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Meta AI Models](../../labs/meta-ai.md)
