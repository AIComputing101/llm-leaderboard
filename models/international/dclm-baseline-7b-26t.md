# DCLM-Baseline 7B 2.6T

> Large Language Model

**Organization:** [International](../../labs/international.md)
**Released:** Jun/2024
**Access:** ❓ Unknown

---

## 📊 Overview

DCLM-Baseline 7B 2.6T is a large language model developed by International.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 7.0B
- **Training Tokens:** 2600.0B
- **Token:Param Ratio:** 372:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.4 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 63.7 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

New dataset: 240T tokens: 8× larger than previous SOTA dataset. DCLM-Pool is 240T, DCLM-Baseline is 3.8T: "we combine our 3.8T DCLM-BASELINE with the StarCoder and ProofPile2 data to arrive at a 4.1T token dataset. We train a 7B model for 2.5T tokens" and "We release the DCLM benchmark, framework, models, and datasets at https://datacomp.ai/dclm."

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/apple/DCLM-Baseline-7B)
- 📄 [Technical Documentation](https://arxiv.org/abs/2406.11794)

## 🔍 Related Models

**From International:**
- See all models in [International profile](../../labs/international.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All International Models](../../labs/international.md)
