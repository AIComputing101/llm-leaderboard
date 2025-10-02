# Zamba2-7B

> Large Language Model

**Organization:** [Zyphra](../../labs/zyphra.md)
**Released:** Oct/2024
**Access:** 🟢 Public

---

## 📊 Overview

Zamba2-7B is a large language model developed by Zyphra.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 7.0B
- **Training Tokens:** 3100.0B
- **Token:Param Ratio:** 443:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.5 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 67.2 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Mamba2 "trained on 128 H100 GPUS for approximately 50 days using our internal training framework developed atop Megatron-LM"

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/Zyphra/Zamba2-7B)
- 📄 [Technical Documentation](https://www.zyphra.com/post/zamba2-7b)

## 🔍 Related Models

**From Zyphra:**
- See all models in [Zyphra profile](../../labs/zyphra.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Zyphra Models](../../labs/zyphra.md)
