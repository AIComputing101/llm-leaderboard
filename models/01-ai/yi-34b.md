# Yi-34B

> Large Language Model

**Organization:** [01-ai](../../labs/01-ai.md)
**Released:** Nov/2023
**Access:** 🟢 Public

---

## 📊 Overview

Yi-34B is a large language model developed by 01-ai.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 34.4B
- **Training Tokens:** 3000.0B
- **Token:Param Ratio:** 88:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 1.1 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 76.3 | General knowledge across 57 subjects |
| **MMLU-Pro** | 43.0 | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Controversy about Llama 2 base. https://twitter.com/kaifulee/status/1724673131875377465 MMLU=76.3 (PaLM 2=78.3) Outperforms Llama 2. Chinese and English. https://www.bloomberg.com/news/articles/2023-11-05/kai-fu-lee-s-open-source-01-ai-bests-llama-2-according-to-hugging-face

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/01-ai/Yi-34B)
- 📄 [Technical Documentation](https://github.com/01-ai/Yi)

## 🔍 Related Models

**From 01-ai:**
- See all models in [01-ai profile](../../labs/01-ai.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All 01-ai Models](../../labs/01-ai.md)
