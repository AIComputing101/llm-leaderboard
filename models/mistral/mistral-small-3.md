# Mistral Small 3

> Large Language Model

**Organization:** [Mistral](../../labs/mistral.md)
**Released:** Jan/2025
**Access:** 🟢 Public

---

## 📊 Overview

Mistral Small 3 is a large language model developed by Mistral.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 24.0B
- **Training Tokens:** 8000.0B
- **Token:Param Ratio:** 334:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 1.5 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 80.73 | General knowledge across 57 subjects |
| **MMLU-Pro** | 54.37 | Advanced MMLU variant |
| **GPQA** | 45.3 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

MMLU=base, -Pro=base, GPQA=instruct. "When quantized, Mistral Small 3 can be run privately on a single RTX 4090 or a Macbook with 32GB RAM." "Mistral Small 3 is neither trained with RL nor synthetic data"

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/mistralai/Mistral-Small-24B-Instruct-2501)
- 📄 [Technical Documentation](https://huggingface.co/mistralai/Mistral-Small-24B-Instruct-2501)

## 🔍 Related Models

**From Mistral:**
- See all models in [Mistral profile](../../labs/mistral.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Mistral Models](../../labs/mistral.md)
