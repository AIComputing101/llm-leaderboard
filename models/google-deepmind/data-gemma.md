# Data-Gemma

> Large Language Model

**Organization:** [Google DeepMind](../../labs/google-deepmind.md)
**Released:** Sep/2024
**Access:** 🟢 Public

---

## 📊 Overview

Data-Gemma is a large language model developed by Google DeepMind.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 27.0B
- **Training Tokens:** 13000.0B
- **Token:Param Ratio:** 482:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 2.0 (Mid-tier)
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

RAG/RIG: "the LLM is fine-tuned to produce natural language Data Commons queries alongside statistics"

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/google/datagemma-rig-27b-it)
- 📄 [Technical Documentation](https://docs.datacommons.org/papers/DataGemma-FullPaper.pdf)

## 🔍 Related Models

**From Google DeepMind:**
- See all models in [Google DeepMind profile](../../labs/google-deepmind.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Google DeepMind Models](../../labs/google-deepmind.md)
