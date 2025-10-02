# YaLM 100B

> Large Language Model

**Organization:** [Yandex](../../labs/yandex.md)
**Released:** Jun/2022
**Access:** 🟢 Public

---

## 📊 Overview

YaLM 100B is a large language model developed by Yandex.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 100.0B
- **Training Tokens:** 300.0B
- **Token:Param Ratio:** 3:1 ⚠️ Under-trained

### Training Efficiency
- **ALScore:** 0.6 (Lightweight)
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

Megatron-LM clone, Russian/English: https://medium.com/yandex/yandex-publishes-yalm-100b-its-the-largest-gpt-like-neural-network-in-open-source-d1df53d0e9a6

## 🔗 Resources

- 🎮 [Try the Model](Github (train/deploy))
- 📄 [Technical Documentation](https://github.com/yandex/YaLM-100B)

## 🔍 Related Models

**From Yandex:**
- See all models in [Yandex profile](../../labs/yandex.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Yandex Models](../../labs/yandex.md)
