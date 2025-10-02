# SmolLM

> Large Language Model

**Organization:** [Hugging Face](../../labs/hugging-face.md)
**Released:** Jul/2024
**Access:** 🟢 Public

---

## 📊 Overview

SmolLM is a large language model developed by Hugging Face.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 1.7B
- **Training Tokens:** 1000.0B
- **Token:Param Ratio:** 589:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.1 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 39.97 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Dataset includes new Cosmopedia v2 synthetic data. 135M and 360M models,each trained on 600B tokens from Smollm-Corpus. 1.7B model trained on 1T tokens from Smollm-Corpus.

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/collections/HuggingFaceTB/smollm-6695016cad7167254ce15966)
- 📄 [Technical Documentation](https://huggingface.co/blog/smollm)

## 🔍 Related Models

**From Hugging Face:**
- See all models in [Hugging Face profile](../../labs/hugging-face.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Hugging Face Models](../../labs/hugging-face.md)
