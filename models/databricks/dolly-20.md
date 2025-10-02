# Dolly 2.0

> Large Language Model

**Organization:** [Databricks](../../labs/databricks.md)
**Released:** Apr/2023
**Access:** 🟢 Public

---

## 📊 Overview

Dolly 2.0 is a large language model developed by Databricks.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 12.0B
- **Training Tokens:** 300.0B
- **Token:Param Ratio:** 25:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.2 (Lightweight)
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

Fine-tuned Pythia 12B

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/databricks/dolly-v2-12b)
- 📄 [Technical Documentation](https://www.databricks.com/blog/2023/04/12/dolly-first-open-commercially-viable-instruction-tuned-llm)

## 🔍 Related Models

**From Databricks:**
- See all models in [Databricks profile](../../labs/databricks.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Databricks Models](../../labs/databricks.md)
