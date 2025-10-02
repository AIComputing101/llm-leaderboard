# Rene

> Large Language Model

**Organization:** [Cartesia](../../labs/cartesia.md)
**Released:** Aug/2024
**Access:** 🟢 Public

---

## 📊 Overview

Rene is a large language model developed by Cartesia.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 1.3B
- **Training Tokens:** 1500.0B
- **Token:Param Ratio:** 1,154:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.1 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 32.6 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

On-device. "hybrid architecture based on Mamba-2, with feedforward and sliding window attention layers interspersed"

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/cartesia-ai/Rene-v0.1-1.3b-pytorch)
- 📄 [Technical Documentation](https://cartesia.ai/blog/2024-08-27-on-device)

## 🔍 Related Models

**From Cartesia:**
- See all models in [Cartesia profile](../../labs/cartesia.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Cartesia Models](../../labs/cartesia.md)
