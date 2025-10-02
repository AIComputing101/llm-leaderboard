# Granite

> Large Language Model

**Organization:** [IBM](../../labs/ibm.md)
**Released:** Sep/2023
**Access:** 🟢 Public

---

## 📊 Overview

Granite is a large language model developed by IBM.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** -
- **Parameters:** 13.0B
- **Training Tokens:** 2500.0B
- **Token:Param Ratio:** 193:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.6 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 57.0 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Original trained on 1T tokens, update 15/Feb/2024 trained on 2.5T tokens: granite-13b-chat-v2 (v2.1.0). "At IBM, we curated 6.48TB of data to train our LLM Granite.13B. This was reduced to 2.07 TB after pre-processing, a 68% decrease."

## 🔗 Resources

- 🎮 [Try the Model](https://www.ibm.com/granite)
- 📄 [Technical Documentation](https://www.ibm.com/downloads/cas/X9W4O6BM)

## 🔍 Related Models

**From IBM:**
- See all models in [IBM profile](../../labs/ibm.md)

**Similar Architecture:**
- See all [- models](../../architectures/.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All IBM Models](../../labs/ibm.md)
