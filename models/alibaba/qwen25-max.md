# Qwen2.5-Max

> Large Language Model

**Organization:** [Alibaba](../../labs/alibaba.md)
**Released:** Jan/2025
**Access:** 🟢 Public

---

## 📊 Overview

Qwen2.5-Max is a large language model developed by Alibaba.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 325.0B
- **Training Tokens:** 20000.0B
- **Token:Param Ratio:** 62:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 8.5 (Powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 87.9 | General knowledge across 57 subjects |
| **MMLU-Pro** | 69.0 | Advanced MMLU variant |
| **GPQA** | 60.1 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

"Qwen2.5-Max emerges as a milestone in MoE development, featuring an impressive 325 billion parameters. The model has been pretrained on over 20 trillion tokens and further refined with advanced post-training methodologies such as Supervised Fine-Tuning (SFT) and Reinforcement Learning from Human Feedback (RLHF)." https://wandb.ai/byyoung3/ml-news/reports/Qwen2-5-Max-Advancing-Large-Scale-Mixture-of-Expert-Models---VmlldzoxMTEyMjUyNg

## 🔗 Resources

- 🎮 [Try the Model](https://chat.qwenlm.ai/)
- 📄 [Technical Documentation](https://qwenlm.github.io/blog/qwen2.5-max/)

## 🔍 Related Models

**From Alibaba:**
- See all models in [Alibaba profile](../../labs/alibaba.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Alibaba Models](../../labs/alibaba.md)
