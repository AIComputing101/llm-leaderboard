# AMD OLMo

> Large Language Model

**Organization:** [AMD](../../labs/amd.md)
**Released:** Nov/2024
**Access:** 🟢 Public

---

## 📊 Overview

AMD OLMo is a large language model developed by AMD.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 1.0B
- **Training Tokens:** 1308.0B
- **Token:Param Ratio:** 1,308:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.1 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 30.52 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

1 billion parameter LMs trained from scratch using 1.3T tokens on a cluster of AMD Instinct MI250 GPUs.

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/amd/AMD-OLMo)
- 📄 [Technical Documentation](https://www.amd.com/en/developer/resources/technical-articles/introducing-the-first-amd-1b-language-model.html)

## 🔍 Related Models

**From AMD:**
- See all models in [AMD profile](../../labs/amd.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All AMD Models](../../labs/amd.md)
