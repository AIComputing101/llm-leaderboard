# Spectra

> Large Language Model

**Organization:** [Consortium](../../labs/consortium.md)
**Released:** Jul/2024
**Access:** 🟢 Public

---

## 📊 Overview

Spectra is a large language model developed by Consortium.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 3.9B
- **Training Tokens:** 300.0B
- **Token:Param Ratio:** 77:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.1 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 32.8 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

AKA TriLM. "Spectra LLM suite, the first open suite of LLMs spanning multiple bit-widths, including FloatLMs, QuantLMs, and TriLMs, ranging from 99M to 3.9B parameters trained on 300B tokens."

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/SpectraSuite)
- 📄 [Technical Documentation](https://arxiv.org/abs/2407.12327)

## 🔍 Related Models

**From Consortium:**
- See all models in [Consortium profile](../../labs/consortium.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Consortium Models](../../labs/consortium.md)
