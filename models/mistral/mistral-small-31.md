# Mistral Small 3.1

> Large Language Model

**Organization:** [Mistral](../../labs/mistral.md)
**Released:** Mar/2025
**Access:** 🟢 Public

---

## 📊 Overview

Mistral Small 3.1 is a large language model developed by Mistral.

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
| **MMLU** | 81.01 | General knowledge across 57 subjects |
| **MMLU-Pro** | 56.03 | Advanced MMLU variant |
| **GPQA** | 37.5 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

"Mistral Small 3.1 (2503) adds state-of-the-art vision understanding and enhances long context capabilities up to 128k tokens without compromising text performance."

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/mistralai/Mistral-Small-3.1-24B-Instruct-2503)
- 📄 [Technical Documentation](https://mistral.ai/news/mistral-small-3-1)

## 🔍 Related Models

**From Mistral:**
- See all models in [Mistral profile](../../labs/mistral.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Mistral Models](../../labs/mistral.md)
