# XGen

> Large Language Model

**Organization:** [Salesforce](../../labs/salesforce.md)
**Released:** Jul/2023
**Access:** 🟢 Public

---

## 📊 Overview

XGen is a large language model developed by Salesforce.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 7.0B
- **Training Tokens:** 1500.0B
- **Token:Param Ratio:** 215:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.3 (Lightweight)
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

8K sequence length. Released under Apache-2.0.

## 🔗 Resources

- 🎮 [Try the Model](https://github.com/salesforce/xgen)
- 📄 [Technical Documentation](https://blog.salesforceairesearch.com/xgen/)

## 🔍 Related Models

**From Salesforce:**
- See all models in [Salesforce profile](../../labs/salesforce.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Salesforce Models](../../labs/salesforce.md)
