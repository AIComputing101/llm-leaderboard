# MPT

> Large Language Model

**Organization:** [MosaicML](../../labs/mosaicml.md)
**Released:** Apr/2023
**Access:** 🟢 Public

---

## 📊 Overview

MPT is a large language model developed by MosaicML.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 1.3B
- **Training Tokens:** 200.0B
- **Token:Param Ratio:** 154:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.1 (Lightweight)
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

More 1B models coming with different datasets. Many more.

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/mosaicml/mpt-1b-redpajama-200b-dolly)
- 📄 [Technical Documentation](https://twitter.com/jefrankle/status/1649060478910357504)

## 🔍 Related Models

**From MosaicML:**
- See all models in [MosaicML profile](../../labs/mosaicml.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All MosaicML Models](../../labs/mosaicml.md)
