# VaultGemma

> Large Language Model

**Organization:** [Google DeepMind](../../labs/google-deepmind.md)
**Released:** Sep/2025
**Access:** 🟢 Public

---

## 📊 Overview

VaultGemma is a large language model developed by Google DeepMind.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 1.0B
- **Training Tokens:** 13000.0B
- **Token:Param Ratio:** 13,000:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.4 (Lightweight)
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

"Differential Privacy (DP) has emerged as the gold standard, providing a rigorous, mathematical framework to limit the influence of any single example in the training data on the resulting model. A model trained with DP provably bounds the reconstruction or leakage of information tied to individual data points." Announce: https://research.google/blog/vaultgemma-the-worlds-most-capable-differentially-private-llm/

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/google/vaultgemma-1b)
- 📄 [Technical Documentation](https://services.google.com/fh/files/blogs/vaultgemma_tech_report.pdf)

## 🔍 Related Models

**From Google DeepMind:**
- See all models in [Google DeepMind profile](../../labs/google-deepmind.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Google DeepMind Models](../../labs/google-deepmind.md)
