# StarCoder 2

> Large Language Model

**Organization:** [HF/ServiceNow](../../labs/hfservicenow.md)
**Released:** Feb/2024
**Access:** 🟢 Public

---

## 📊 Overview

StarCoder 2 is a large language model developed by HF/ServiceNow.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 15.0B
- **Training Tokens:** 4300.0B
- **Token:Param Ratio:** 287:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.8 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** code, The Stack

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

The Stack v2=900B tokens, 5 epochs to 4.3T tokens

## 🔗 Resources

- 📄 [Technical Documentation](https://arxiv.org/abs/2402.19173)

## 🔍 Related Models

**From HF/ServiceNow:**
- See all models in [HF/ServiceNow profile](../../labs/hfservicenow.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All HF/ServiceNow Models](../../labs/hfservicenow.md)
