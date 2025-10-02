# Med-PaLM 2

> Large Language Model

**Organization:** [Google DeepMind](../../labs/google-deepmind.md)
**Released:** Mar/2023
**Access:** 🔴 Private

---

## 📊 Overview

Med-PaLM 2 is a large language model developed by Google DeepMind.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 340.0B
- **Training Tokens:** 3600.0B
- **Token:Param Ratio:** 11:1 ⚠️ Under-trained

### Training Efficiency
- **ALScore:** 3.7 (Mid-tier)
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

Recently, our next iteration, Med-PaLM 2, consistently performed at an “expert” doctor level on medical exam questions, scoring 85%. This is an 18% improvement from Med-PaLM’s previous performance and far surpasses similar AI models.

## 🔗 Resources

- 📄 [Technical Documentation](https://blog.google/technology/health/ai-llm-medpalm-research-thecheckup/)

## 🔍 Related Models

**From Google DeepMind:**
- See all models in [Google DeepMind profile](../../labs/google-deepmind.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Google DeepMind Models](../../labs/google-deepmind.md)
