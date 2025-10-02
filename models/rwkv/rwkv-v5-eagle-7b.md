# RWKV-v5 Eagle 7B

> Large Language Model

**Organization:** [RWKV](../../labs/rwkv.md)
**Released:** Jan/2024
**Access:** 🟢 Public

---

## 📊 Overview

RWKV-v5 Eagle 7B is a large language model developed by RWKV.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 7.52B
- **Training Tokens:** 1100.0B
- **Token:Param Ratio:** 147:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.3 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 33.21 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

RWKV (pronounced RwaKuv) is an RNN: Built on the RWKV-v5 architecture (a linear transformer with 10-100x+ lower inference cost), Trained on 1.1 Trillion Tokens across 100+ languages. Original paper: https://arxiv.org/abs/2305.13048

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/spaces/BlinkDL/RWKV-Gradio-2)
- 📄 [Technical Documentation](https://blog.rwkv.com/p/eagle-7b-soaring-past-transformers)

## 🔍 Related Models

**From RWKV:**
- See all models in [RWKV profile](../../labs/rwkv.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All RWKV Models](../../labs/rwkv.md)
