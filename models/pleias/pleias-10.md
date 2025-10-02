# Pleias 1.0

> Large Language Model

**Organization:** [PleIAs](../../labs/pleias.md)
**Released:** Dec/2024
**Access:** 🟢 Public

---

## 📊 Overview

Pleias 1.0 is a large language model developed by PleIAs.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 3.0B
- **Training Tokens:** 1086.0B
- **Token:Param Ratio:** 362:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.2 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

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

Trained on the Jean Zay supercomputer, 192x H100s for 20 days. Dataset is new CC + Synthetic: https://huggingface.co/datasets/PleIAs/common_corpus

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/PleIAs/Pleias-3b-Preview)
- 📄 [Technical Documentation](https://huggingface.co/blog/Pclanglais/common-models)

## 🔍 Related Models

**From PleIAs:**
- See all models in [PleIAs profile](../../labs/pleias.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All PleIAs Models](../../labs/pleias.md)
