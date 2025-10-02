# TÜLU 3

> Large Language Model

**Organization:** [Allen AI](../../labs/allen-ai.md)
**Released:** Nov/2024
**Access:** 🟢 Public

---

## 📊 Overview

TÜLU 3 is a large language model developed by Allen AI.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 70.0B
- **Training Tokens:** 15600.0B
- **Token:Param Ratio:** 223:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 3.5 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 83.1 | General knowledge across 57 subjects |
| **MMLU-Pro** | 65.8 | Advanced MMLU variant |
| **GPQA** | 45.1 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Llama 3.1 post-training, worse performance on most benchmarks. Post training methods include new Reinforcement Learning with Verifiable Rewards (RLVR). "We perform supervised fine-tuning on new capability-focused synthetic data mixed with existing instruction datasets. We then perform preference tuning on on-policy synthetic preference data. We finish training Llama Tülu3 with our new method, Reinforcement Learning with Verifiable Rewards."

## 🔗 Resources

- 🎮 [Try the Model](https://playground.allenai.org/)
- 📄 [Technical Documentation](https://allenai.org/papers/tulu-3-report.pdf)

## 🔍 Related Models

**From Allen AI:**
- See all models in [Allen AI profile](../../labs/allen-ai.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Allen AI Models](../../labs/allen-ai.md)
