# DeciLM

> Large Language Model

**Organization:** [Deci](../../labs/deci.md)
**Released:** Sep/2023
**Access:** 🟢 Public

---

## 📊 Overview

DeciLM is a large language model developed by Deci.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 5.7B
- **Training Tokens:** 200.0B
- **Token:Param Ratio:** 36:1 ✅ Compute-optimal

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

Faster inference (4.8× throughput of Llama 2)

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/Deci/DeciLM-6b)
- 📄 [Technical Documentation](https://deci.ai/blog/decilm-15-times-faster-than-llama2-nas-generated-llm-with-variable-gqa/)

## 🔍 Related Models

**From Deci:**
- See all models in [Deci profile](../../labs/deci.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Deci Models](../../labs/deci.md)
