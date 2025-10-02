# T5Gemma

> Large Language Model

**Organization:** [Google DeepMind](../../labs/google-deepmind.md)
**Released:** Jul/2025
**Access:** 🟢 Public

---

## 📊 Overview

T5Gemma is a large language model developed by Google DeepMind.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 9.0B
- **Training Tokens:** 10000.0B
- **Token:Param Ratio:** 1,112:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 1.0 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 76.7 | General knowledge across 57 subjects |
| **MMLU-Pro** | 55.7 | Advanced MMLU variant |
| **GPQA** | 40.4 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Related paper: https://arxiv.org/abs/2504.06225. Dataset was Gemma 2 9B on 8T tokens + 2T tokens adapted.

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/google/t5gemma-9b-9b-ul2-it)
- 📄 [Technical Documentation](https://developers.googleblog.com/en/t5gemma/)

## 🔍 Related Models

**From Google DeepMind:**
- See all models in [Google DeepMind profile](../../labs/google-deepmind.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Google DeepMind Models](../../labs/google-deepmind.md)
