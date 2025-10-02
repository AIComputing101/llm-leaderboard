# Unified-IO 2

> Large Language Model

**Organization:** [Allen AI](../../labs/allen-ai.md)
**Released:** Dec/2023
**Access:** 🟢 Public

---

## 📊 Overview

Unified-IO 2 is a large language model developed by Allen AI.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 7.0B
- **Training Tokens:** 1000.0B
- **Token:Param Ratio:** 143:1 ✅ Compute-optimal

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

600TB dataset (plus 120+ fine-tuning datasets) includes '1B imagetext pairs, 1T text tokens, 180M video clips, 130M interleaved image & text, 3M 3D assets, and 1M agent trajectories.'

## 🔗 Resources

- 🎮 [Try the Model](https://unified-io-2.allenai.org/)
- 📄 [Technical Documentation](https://arxiv.org/abs/2312.17172)

## 🔍 Related Models

**From Allen AI:**
- See all models in [Allen AI profile](../../labs/allen-ai.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Allen AI Models](../../labs/allen-ai.md)
