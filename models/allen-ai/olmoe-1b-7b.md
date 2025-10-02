# OLMoE-1B-7B

> Large Language Model

**Organization:** [Allen AI](../../labs/allen-ai.md)
**Released:** Sep/2024
**Access:** 🟢 Public

---

## 📊 Overview

OLMoE-1B-7B is a large language model developed by Allen AI.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 6.9B
- **Training Tokens:** 5900.0B
- **Token:Param Ratio:** 856:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.7 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 54.1 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | 23.0 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Open Language (OL) Mixture of Experts (MoE). "We train OLMoE-1B-7B for 5 trillion tokens, however, some recent dense models train significantly longer, such as Llama 3 with 15 trillion tokens. To the best of our knowledge, there has been no large MoE that has been overtrained as much as OLMoE-1B-7B. Specifically, taking the active parameters of OLMoE-1B-7B, our token multiplier is around 5,000 (5T / 1B). There are likely benefits to training even longer, but to what degree overtraining is effective for MoEs and how it differs from dense models still requires more research."

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/collections/allenai/olmoe-66cf678c047657a30c8cd3da)
- 📄 [Technical Documentation](https://arxiv.org/abs/2409.02060v1)

## 🔍 Related Models

**From Allen AI:**
- See all models in [Allen AI profile](../../labs/allen-ai.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Allen AI Models](../../labs/allen-ai.md)
