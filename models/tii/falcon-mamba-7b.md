# Falcon Mamba 7B

> Large Language Model

**Organization:** [TII](../../labs/tii.md)
**Released:** Aug/2024
**Access:** 🟢 Public

---

## 📊 Overview

Falcon Mamba 7B is a large language model developed by TII.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 7.0B
- **Training Tokens:** 6000.0B
- **Token:Param Ratio:** 858:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.7 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 62.11 | General knowledge across 57 subjects |
| **MMLU-Pro** | 14.47 | Advanced MMLU variant |
| **GPQA** | 8.05 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

https://huggingface.co/spaces/tiiuae/falcon-mamba-playground

## 🔗 Resources

- 🎮 [Try the Model](https://falconllm.tii.ae/falcon-models.html)
- 📄 [Technical Documentation](https://falconllm.tii.ae/tii-releases-first-sslm-with-falcon-mamba-7b.html)

## 🔍 Related Models

**From TII:**
- See all models in [TII profile](../../labs/tii.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All TII Models](../../labs/tii.md)
