# Apriel-5B

> Large Language Model

**Organization:** [ServiceNow](../../labs/servicenow.md)
**Released:** Apr/2025
**Access:** 🟢 Public

---

## 📊 Overview

Apriel-5B is a large language model developed by ServiceNow.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 5.0B
- **Training Tokens:** 4500.0B
- **Token:Param Ratio:** 900:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.5 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 61.3 | General knowledge across 57 subjects |
| **MMLU-Pro** | 29.19 | Advanced MMLU variant |
| **GPQA** | 28.36 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

SLAM - ServiceNow Language Models Lab. The first release in the Apriel model family, designed to support research on foundation models.

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/ServiceNow-AI/Apriel-5B-Instruct)
- 📄 [Technical Documentation](https://huggingface.co/ServiceNow-AI/Apriel-5B-Instruct)

## 🔍 Related Models

**From ServiceNow:**
- See all models in [ServiceNow profile](../../labs/servicenow.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All ServiceNow Models](../../labs/servicenow.md)
