# Comma v0.1-2T

> Large Language Model

**Organization:** [EleutherAI](../../labs/eleutherai.md)
**Released:** Jun/2025
**Access:** 🟢 Public

---

## 📊 Overview

Comma v0.1-2T is a large language model developed by EleutherAI.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 7.0B
- **Training Tokens:** 2000.0B
- **Token:Param Ratio:** 286:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.4 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 49.8 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

"Comma v0.1-2T is a decoder-only transformer that uses the same architecture as Llama 3. Training was done in two stages: first on 1.93 trillion tokens with a cosine learning rate schedule, and second a "cool-down" training phase on 75.5 billion tokens from high-quality sources. The final model is the average of 10 checkpoints during this cool-down phase. Both training phases use a batch size of 8.3 million tokens per step. Training was performed using lingua on 512 AMD MI300A GPUs."

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/common-pile/comma-v0.1-2t)
- 📄 [Technical Documentation](https://arxiv.org/abs/2506.05209)

## 🔍 Related Models

**From EleutherAI:**
- See all models in [EleutherAI profile](../../labs/eleutherai.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All EleutherAI Models](../../labs/eleutherai.md)
