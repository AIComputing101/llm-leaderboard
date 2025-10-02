# MoLM

> Large Language Model

**Organization:** [IBM](../../labs/ibm.md)
**Released:** Sep/2023
**Access:** 🟢 Public

---

## 📊 Overview

MoLM is a large language model developed by IBM.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 8.0B
- **Training Tokens:** 300.0B
- **Token:Param Ratio:** 38:1 ✅ Compute-optimal

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

ModuleFormer is based on the Sparse Mixture of Experts (MoE).

## 🔗 Resources

- 🎮 [Try the Model](https://github.com/ibm/moduleformer)
- 📄 [Technical Documentation](https://arxiv.org/abs/2306.04640)

## 🔍 Related Models

**From IBM:**
- See all models in [IBM profile](../../labs/ibm.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All IBM Models](../../labs/ibm.md)
