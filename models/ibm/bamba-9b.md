# Bamba-9B

> Large Language Model

**Organization:** [IBM](../../labs/ibm.md)
**Released:** Dec/2024
**Access:** 🟢 Public

---

## 📊 Overview

Bamba-9B is a large language model developed by IBM.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 9.0B
- **Training Tokens:** 2200.0B
- **Token:Param Ratio:** 245:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.5 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 60.77 | General knowledge across 57 subjects |
| **MMLU-Pro** | 17.53 | Advanced MMLU variant |
| **GPQA** | 4.14 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

"trained by IBM, Princeton, CMU, and UIUC on completely open data. At inference time, the model demonstrates 2.5x throughput improvement and 2x latency speedup compared to standard transformers in vLLM."

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/blog/bamba)
- 📄 [Technical Documentation](https://huggingface.co/blog/bamba)

## 🔍 Related Models

**From IBM:**
- See all models in [IBM profile](../../labs/ibm.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All IBM Models](../../labs/ibm.md)
