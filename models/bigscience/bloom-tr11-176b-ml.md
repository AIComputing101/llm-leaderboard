# BLOOM (tr11-176B-ml)

> Large Language Model

**Organization:** [BigScience](../../labs/bigscience.md)
**Released:** Jul/2022
**Access:** 🟢 Public

---

## 📊 Overview

BLOOM (tr11-176B-ml) is a large language model developed by BigScience.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 176.0B
- **Training Tokens:** 366.0B
- **Token:Param Ratio:** 3:1 ⚠️ Under-trained

### Training Efficiency
- **ALScore:** 0.8 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 39.1 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

_No additional notes available._

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/spaces/huggingface/bloom_demo)
- 📄 [Technical Documentation](https://github.com/bigscience-workshop/bigscience/tree/master/train/tr11-176B-ml)

## 🔍 Related Models

**From BigScience:**
- See all models in [BigScience profile](../../labs/bigscience.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All BigScience Models](../../labs/bigscience.md)
