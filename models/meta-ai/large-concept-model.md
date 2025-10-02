# Large Concept Model

> Large Language Model

**Organization:** [Meta AI](../../labs/meta-ai.md)
**Released:** Dec/2024
**Access:** 🟢 Public

---

## 📊 Overview

Large Concept Model is a large language model developed by Meta AI.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 7.0B
- **Training Tokens:** 2700.0B
- **Token:Param Ratio:** 386:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.5 (Lightweight)
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

"autoregressive sentence prediction in an embedding space." 7.7T tokens is a misprint, should be 2.2T as in paper.

## 🔗 Resources

- 🎮 [Try the Model](https://github.com/facebookresearch/large_concept_model?tab=readme-ov-file)
- 📄 [Technical Documentation](https://ai.meta.com/research/publications/large-concept-models-language-modeling-in-a-sentence-representation-space/)

## 🔍 Related Models

**From Meta AI:**
- See all models in [Meta AI profile](../../labs/meta-ai.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Meta AI Models](../../labs/meta-ai.md)
