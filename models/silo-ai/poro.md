# Poro

> Large Language Model

**Organization:** [Silo AI](../../labs/silo-ai.md)
**Released:** Feb/2024
**Access:** 🟢 Public

---

## 📊 Overview

Poro is a large language model developed by Silo AI.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 34.2B
- **Training Tokens:** 1000.0B
- **Token:Param Ratio:** 30:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.6 (Lightweight)
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

Uses a BLOOM architecture with ALiBi embeddings to allow for context window extrapolation. While model architecture for the initial model has been kept simple, future models under progress will support additional capabilities, such as flash attention, rotary embeddings and grouped query attention.'

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/LumiOpen/Poro-34B)
- 📄 [Technical Documentation](https://www.silo.ai/blog/viking-7b-13b-33b-sailing-the-nordic-seas-of-multilinguality)

## 🔍 Related Models

**From Silo AI:**
- See all models in [Silo AI profile](../../labs/silo-ai.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Silo AI Models](../../labs/silo-ai.md)
