# Cosmo-1B

> Large Language Model

**Organization:** [HF](../../labs/hf.md)
**Released:** Feb/2024
**Access:** 🟢 Public

---

## 📊 Overview

Cosmo-1B is a large language model developed by HF.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 1.8B
- **Training Tokens:** 180.0B
- **Token:Param Ratio:** 100:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.1 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic

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

Synthetic data (25B tokens of synthetic data for 6 epochs + code). MMLU=32.4

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/HuggingFaceTB/cosmo-1b)
- 📄 [Technical Documentation](https://huggingface.co/blog/cosmopedia)

## 🔍 Related Models

**From HF:**
- See all models in [HF profile](../../labs/hf.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All HF Models](../../labs/hf.md)
