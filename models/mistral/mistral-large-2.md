# Mistral Large 2

> Large Language Model

**Organization:** [Mistral](../../labs/mistral.md)
**Released:** Jul/2024
**Access:** 🟢 Public

---

## 📊 Overview

Mistral Large 2 is a large language model developed by Mistral.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 123.0B
- **Training Tokens:** 8000.0B
- **Token:Param Ratio:** 66:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 3.3 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 84.0 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Fits on a single node for inference.

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/mistralai/Mistral-Large-Instruct-2407)
- 📄 [Technical Documentation](https://mistral.ai/news/mistral-large-2407/)

## 🔍 Related Models

**From Mistral:**
- See all models in [Mistral profile](../../labs/mistral.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Mistral Models](../../labs/mistral.md)
