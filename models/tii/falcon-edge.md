# Falcon-Edge

> Large Language Model

**Organization:** [TII](../../labs/tii.md)
**Released:** May/2025
**Access:** 🟢 Public

---

## 📊 Overview

Falcon-Edge is a large language model developed by TII.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 3.0B
- **Training Tokens:** 1500.0B
- **Token:Param Ratio:** 500:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.2 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 55.7 | General knowledge across 57 subjects |
| **MMLU-Pro** | 27.16 | Advanced MMLU variant |
| **GPQA** | 23.59 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

"Falcon-Edge series - a collection of powerful, universal, and fine-tunable language models available in ternary format, based on the BitNet architecture."

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/tiiuae/Falcon-E-3B-Instruct)
- 📄 [Technical Documentation](https://huggingface.co/blog/tiiuae/falcon-edge)

## 🔍 Related Models

**From TII:**
- See all models in [TII profile](../../labs/tii.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All TII Models](../../labs/tii.md)
