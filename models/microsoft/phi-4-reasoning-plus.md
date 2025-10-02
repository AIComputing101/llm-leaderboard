# Phi-4-reasoning-plus

> Large Language Model

**Organization:** [Microsoft](../../labs/microsoft.md)
**Released:** Apr/2025
**Access:** 🟢 Public

---

## 📊 Overview

Phi-4-reasoning-plus is a large language model developed by Microsoft.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 14.0B
- **Training Tokens:** 10016.0B
- **Token:Param Ratio:** 716:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 1.2 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | 76.0 | Advanced MMLU variant |
| **GPQA** | 69.3 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

"Phi-4-reasoning-plus is a state-of-the-art open-weight reasoning model finetuned from Phi-4 using supervised fine-tuning on a dataset of chain-of-thought traces and reinforcement learning."

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/microsoft/Phi-4-reasoning-plus)
- 📄 [Technical Documentation](https://arxiv.org/abs/2504.21318)

## 🔍 Related Models

**From Microsoft:**
- See all models in [Microsoft profile](../../labs/microsoft.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Microsoft Models](../../labs/microsoft.md)
