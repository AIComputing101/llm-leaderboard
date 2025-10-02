# DBRX

> Large Language Model

**Organization:** [MosaicML](../../labs/mosaicml.md)
**Released:** Mar/2024
**Access:** 🟢 Public

---

## 📊 Overview

DBRX is a large language model developed by MosaicML.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 132.0B
- **Training Tokens:** 12000.0B
- **Token:Param Ratio:** 91:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 4.2 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 73.7 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

MoE. Trained for $10M on 3,072 NVIDIA H100s connected by 3.2Tbps Infiniband.

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/spaces/databricks/dbrx-instruct)
- 📄 [Technical Documentation](https://www.databricks.com/blog/introducing-dbrx-new-state-art-open-llm)

## 🔍 Related Models

**From MosaicML:**
- See all models in [MosaicML profile](../../labs/mosaicml.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All MosaicML Models](../../labs/mosaicml.md)
