# Med-Gemini-L 1.0

> Large Language Model

**Organization:** [Google DeepMind](../../labs/google-deepmind.md)
**Released:** May/2024
**Access:** 🔴 Private

---

## 📊 Overview

Med-Gemini-L 1.0 is a large language model developed by Google DeepMind.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 200.0B
- **Training Tokens:** 30000.0B
- **Token:Param Ratio:** 150:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 8.2 (Powerful)
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

Med-Gemini-M 1.0 and Med-Gemini-L 1.0 (Pro and Ultra finetunes) "For language tasks that require less complex reasoning, such as summarizing medical notes and creating referral letters, we introduce Med-Gemini-M 1.0 by fine-tuning the Gemini 1.0 Pro model. For other tasks that require more advanced reasoning, we introduce Med-Gemini-L 1.0 by fine-tuning the Gemini 1.0 Ultra model using a self-training method to enable the models to efficiently use web search."

## 🔗 Resources

- 🎮 [Try the Model](https://twitter.com/alan_karthi/status/1785117450528264216)
- 📄 [Technical Documentation](https://arxiv.org/abs/2404.18416)

## 🔍 Related Models

**From Google DeepMind:**
- See all models in [Google DeepMind profile](../../labs/google-deepmind.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Google DeepMind Models](../../labs/google-deepmind.md)
