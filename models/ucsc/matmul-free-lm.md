# MatMul-Free LM

> Large Language Model

**Organization:** [UCSC](../../labs/ucsc.md)
**Released:** Jun/2024
**Access:** 🟢 Public

---

## 📊 Overview

MatMul-Free LM is a large language model developed by UCSC.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 2.7B
- **Training Tokens:** 100.0B
- **Token:Param Ratio:** 38:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.1 (Lightweight)
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

"we explore alternative methods for mixing tokens without relying on matrix multiplications." Compared with Transformer++ based on Llama-2, not to be confused with the pre-GPT-3 American Express Transformer++ paper from 2/Mar/2020. Instead, Transformer++ is defined in the Mamba paper: 'Transformer++: A Transformer with an improved architecture, namely rotary positional encodings (Su et al. 2021) and SwiGLU MLP (Shazeer 2020)'

## 🔗 Resources

- 🎮 [Try the Model](https://github.com/ridgerchu/matmulfreellm)
- 📄 [Technical Documentation](https://arxiv.org/abs/2406.02528)

## 🔍 Related Models

**From UCSC:**
- See all models in [UCSC profile](../../labs/ucsc.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All UCSC Models](../../labs/ucsc.md)
