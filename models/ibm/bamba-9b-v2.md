# Bamba-9B-v2

> Large Language Model

**Organization:** [IBM](../../labs/ibm.md)
**Released:** Apr/2025
**Access:** 🟢 Public

---

## 📊 Overview

Bamba-9B-v2 is a large language model developed by IBM.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 9.0B
- **Training Tokens:** 3000.0B
- **Token:Param Ratio:** 334:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.5 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 67.92 | General knowledge across 57 subjects |
| **MMLU-Pro** | 25.41 | Advanced MMLU variant |
| **GPQA** | 5.93 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

"During Christmas of 2024, IBM, Princeton, CMU, and UIUC released, Bamba v1, a performant Mamba2 based pretrained model with full data lineage trained to 2T tokens. Since then, we have been busy cooking an update with new datasets. Today, we are excited to release Bamba v2, trained for an additional 1T tokens that significantly improves on Bamba v1. The L1 and L2 leaderboard scores outperform Llama 3.1 8B, which was trained with nearly 5x the amount of data. All of this with the inference speedup that we get from Mamba2 based architecture, which with the latest vLLM is 2-2.5x faster than similar sized transformer models."

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/ibm-ai-platform/Bamba-9B-v2)
- 📄 [Technical Documentation](https://huggingface.co/blog/ibm-ai-platform/bamba-9b-v2)

## 🔍 Related Models

**From IBM:**
- See all models in [IBM profile](../../labs/ibm.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All IBM Models](../../labs/ibm.md)
