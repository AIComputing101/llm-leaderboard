# BloombergGPT

> Large Language Model

**Organization:** [Bloomberg](../../labs/bloomberg.md)
**Released:** Mar/2023
**Access:** 🔴 Private

---

## 📊 Overview

BloombergGPT is a large language model developed by Bloomberg.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 50.0B
- **Training Tokens:** 569.0B
- **Token:Param Ratio:** 12:1 ⚠️ Under-trained

### Training Efficiency
- **ALScore:** 0.6 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 39.2 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Video: https://youtu.be/m2Scj2SO85Y Underperforms GPT-3, based on BLOOM. Tokens: 'We select a model size motivated by Hoffmann et al. (2022) and train a 50 billion parameter model on 569 billion tokens from our corpus of over 700 billion tokens to produce a model that is competitive with larger models.'

## 🔗 Resources

- 📄 [Technical Documentation](https://arxiv.org/abs/2303.17564)

## 🔍 Related Models

**From Bloomberg:**
- See all models in [Bloomberg profile](../../labs/bloomberg.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Bloomberg Models](../../labs/bloomberg.md)
