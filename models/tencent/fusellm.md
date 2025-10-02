# FuseLLM

> Large Language Model

**Organization:** [Tencent](../../labs/tencent.md)
**Released:** Jan/2024
**Access:** 🟢 Public

---

## 📊 Overview

FuseLLM is a large language model developed by Tencent.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 7.0B
- **Training Tokens:** 2000.0B
- **Token:Param Ratio:** 286:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.4 (Lightweight)
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

Fusion of Llama-2-7B (2T tok), OpenLLaMA-7B (2T tok), and MPT-7B (1T tok).

## 🔗 Resources

- 🎮 [Try the Model](https://github.com/fanqiwan/FuseLLM)
- 📄 [Technical Documentation](https://arxiv.org/abs/2401.10491)

## 🔍 Related Models

**From Tencent:**
- See all models in [Tencent profile](../../labs/tencent.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Tencent Models](../../labs/tencent.md)
