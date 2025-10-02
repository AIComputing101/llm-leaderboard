# BTLM-3B-8K

> Large Language Model

**Organization:** [Cerebras](../../labs/cerebras.md)
**Released:** Jul/2023
**Access:** 🟢 Public

---

## 📊 Overview

BTLM-3B-8K is a large language model developed by Cerebras.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 3.0B
- **Training Tokens:** 627.0B
- **Token:Param Ratio:** 209:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.1 (Lightweight)
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

Runs on devices with as little as 3GB of memory [iPhone, Macbook] when quantized to 4-bit

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/cerebras/btlm-3b-8k-base)
- 📄 [Technical Documentation](https://www.cerebras.net/blog/btlm-3b-8k-7b-performance-in-a-3-billion-parameter-model/)

## 🔍 Related Models

**From Cerebras:**
- See all models in [Cerebras profile](../../labs/cerebras.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Cerebras Models](../../labs/cerebras.md)
