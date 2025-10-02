# EvaByte

> Large Language Model

**Organization:** [SambaNova](../../labs/sambanova.md)
**Released:** Jan/2025
**Access:** 🟢 Public

---

## 📊 Overview

EvaByte is a large language model developed by SambaNova.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 6.5B
- **Training Tokens:** 1500.0B
- **Token:Param Ratio:** 231:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.3 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 50.6 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

"efficient byte-level processing at scale... [compared to tokenizer-based LMs:] 5x less training data, excelling in coding tasks, and decoding up to 2x faster. Its token-free design also brings added flexibility, avoiding tokenizer quirks while naturally extending to multimodal applications without any architecture tweaks."

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/EvaByte/EvaByte)
- 📄 [Technical Documentation](https://hkunlp.github.io/blog/2025/evabyte/)

## 🔍 Related Models

**From SambaNova:**
- See all models in [SambaNova profile](../../labs/sambanova.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All SambaNova Models](../../labs/sambanova.md)
