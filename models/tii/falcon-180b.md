# Falcon 180B

> Large Language Model

**Organization:** [TII](../../labs/tii.md)
**Released:** Sep/2023
**Access:** 🟢 Public

---

## 📊 Overview

Falcon 180B is a large language model developed by TII.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 180.0B
- **Training Tokens:** 3500.0B
- **Token:Param Ratio:** 20:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 2.6 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 70.6 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Major milestone for open source models (largest open dense model to date).

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/spaces/tiiuae/falcon-180b-demo)
- 📄 [Technical Documentation](https://arxiv.org/abs/2311.16867)

## 🔍 Related Models

**From TII:**
- See all models in [TII profile](../../labs/tii.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All TII Models](../../labs/tii.md)
