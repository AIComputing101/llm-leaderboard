# RWKV-v5 EagleX

> Large Language Model

**Organization:** [RWKV](../../labs/rwkv.md)
**Released:** Mar/2024
**Access:** 🟢 Public

---

## 📊 Overview

RWKV-v5 EagleX is a large language model developed by RWKV.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 7.52B
- **Training Tokens:** 1700.0B
- **Token:Param Ratio:** 227:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.4 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 40.14 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

RWKV (pronounced RwaKuv) is an RNN: Built on the RWKV-v5 architecture (a linear transformer with 10-100x+ lower inference cost)

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/recursal/EagleX_1-7T)
- 📄 [Technical Documentation](https://substack.recursal.ai/p/eaglex-17t-soaring-past-llama-7b)

## 🔍 Related Models

**From RWKV:**
- See all models in [RWKV profile](../../labs/rwkv.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All RWKV Models](../../labs/rwkv.md)
