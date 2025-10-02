# Tele-FLM

> Large Language Model

**Organization:** [BAAI](../../labs/baai.md)
**Released:** Apr/2024
**Access:** 🟢 Public

---

## 📊 Overview

Tele-FLM is a large language model developed by BAAI.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 52.0B
- **Training Tokens:** 2000.0B
- **Token:Param Ratio:** 39:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 1.1 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 64.0 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Also known as FLM-2. "We will open-source a 1T model checkpoint, namely Tele-FLM-1T, to advance further training and research." Discussion paper Jul/2024: https://arxiv.org/abs/2407.02783

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/CofeAI/Tele-FLM)
- 📄 [Technical Documentation](https://arxiv.org/abs/2404.16645)

## 🔍 Related Models

**From BAAI:**
- See all models in [BAAI profile](../../labs/baai.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All BAAI Models](../../labs/baai.md)
