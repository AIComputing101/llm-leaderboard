# Sky-T1-32B-Preview

> Large Language Model

**Organization:** [Berkeley](../../labs/berkeley.md)
**Released:** Jan/2025
**Access:** 🟢 Public

---

## 📊 Overview

Sky-T1-32B-Preview is a large language model developed by Berkeley.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 32.0B
- **Training Tokens:** 18000.0B
- **Token:Param Ratio:** 563:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 2.5 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | 56.8 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

"To generate our training data we use QwQ-32B-Preview, an open-source model with reasoning capabilities comparable to o1-preview. We curate the data mixture (see later section) to cover diverse domains that require reasoning, and a reject sampling procedure to improve the data quality. We then rewrite QwQ traces with GPT-4o-mini into a well-formatted version, inspired by Still-2, to improve data quality and ease parsing... Rejection Sampling: We discard QwQ samples if they are incorrect according to the solutions provided in datasets."

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/NovaSky-AI/Sky-T1-32B-Preview)
- 📄 [Technical Documentation](https://novasky-ai.github.io/posts/sky-t1/)

## 🔍 Related Models

**From Berkeley:**
- See all models in [Berkeley profile](../../labs/berkeley.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Berkeley Models](../../labs/berkeley.md)
