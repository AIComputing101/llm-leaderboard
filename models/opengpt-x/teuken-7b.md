# Teuken-7B

> Large Language Model

**Organization:** [OpenGPT-X](../../labs/opengpt-x.md)
**Released:** Nov/2024
**Access:** 🟢 Public

---

## 📊 Overview

Teuken-7B is a large language model developed by OpenGPT-X.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 7.0B
- **Training Tokens:** 4000.0B
- **Token:Param Ratio:** 572:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.6 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 50.0 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

24 EU languages (60% non-English): bg, cs, da, de, el, en, es, et, fi, fr, ga, hr, hu, it, lt, lv, mt, nl, pl, pt, ro, sk, sl, sv. https://opengpt-x.de/models/teuken-7b-de/ & paper date is Sep/2024.

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/openGPT-X/Teuken-7B-instruct-research-v0.4)
- 📄 [Technical Documentation](https://arxiv.org/abs/2410.03730)

## 🔍 Related Models

**From OpenGPT-X:**
- See all models in [OpenGPT-X profile](../../labs/opengpt-x.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All OpenGPT-X Models](../../labs/opengpt-x.md)
